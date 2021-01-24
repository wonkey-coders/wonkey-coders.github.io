
# The command-line compiler

**`wake`** is the command-line compiler for Wonkey.

!!! attention "Please note"
    The actual executable name of the command-line compiler is different and depends on the operating system!

## The compiler binary

The Wonkey compiler **`wake`** is located in the **`bin/`** directory of your Wonkey installation.<br/>
See the following table for the actual executable name on each host platform:

| Platform     | Compiler binary
|:-------------|-------------------------
| Windows      | **/bin/windows/wake.exe**
| Linux        | **/bin/linux/wake**
| macOS        | **/bin/macos/wake**
| Raspberry Pi | **/bin/raspbian/wake**

!!! hint
    If you add the **`Wonkey/bin/%OS%`** directory to your **`PATH`** environment variable,
    you are able to use the Wonkey compiler directly from every directory on the command-line or in a terminal.

## Compiler usage

The command-line options for **`wake`** are:

**`wake`** **command** **options** **input**

## Compiler commands

| Command        | Description
|:---------------|------------
| **app**  | Build an application.<br/> **_input_** should be a \*\.wx file.
| **mods** | Build module(s).<br/> **_input_** should be a space separated list of module names, or nothing to make all modules.
| **docs** | Build the documentation for a set of modules.<br/> **_input_** should be a space separated list of module names, or nothing to make all modules.

## Compiler options

| Option                     | Description
|:---------------------------|------------
| **-quiet**                 | Emit less info when building.
| **-verbose=**              | Emit more info when building, one of: none, 0 to 3. (Defaults: 1 or -1 if quiet).
| **-clean**                 | Force clean rebuild.
| **-time**                  | Output build time information.
| **-parse**                 | Parse only. Checks for parsing errors.
| **-semant**                | Parse and semant. Checks for parsing and semantic errors.
| **-translate**             | Parse, semant and translate.
| **-build**                 | Parse, semant, translate and build.
| **-run**                   | Runs the application after successful build.
| **-target=**==_target_==   | Set ==_target_== to one of the following values:<br/>**desktop** (default: alias for current host),<br/>**windows**, **macos**, **linux**, **raspbian**,<br/>**android**, **ios**, **emscripten**, **wasm**
| **-config=**==_config_==   | Set ==_config_== to:<br/>**debug**, **release**, or **all**.<br>(Defaults: `all` for modules else `debug`)
| **-apptype=**==_apptype_== | Set ==_apptype_== to:<br/>**gui** (default) or **console**
| **-product=**==_path_==    | ==_path_== is the build output path

## Examples

Compile a desktop gui app in debug mode (default) and run it:

**`wake app main.wx`**

Compile a console application in release mode for the host operating system and run it:

**`wake app -config=release -apptype=console myfile.wx`**

Compile a game for the 'iOS' target:

**`wake app -config=release -target=ios mygame.wx`**

Build the complete docs:

**`wake docs`**

Force clean rebuild of all modules for the 'Android' target in release and debug mode:

**`wake mods -clean -target=android -config=debug`**<br/>
**`wake mods -clean -target=android -config=release`**

Compile your own module 'mymodule'. The module/library must be located in the 'modules' directory.

**`wake mods -config=debug mymodule`**<br/>
**`wake mods -config=release mymodule`**
