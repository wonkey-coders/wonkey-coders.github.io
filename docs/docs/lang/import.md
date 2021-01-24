# Import

<!--
## The build system
-->

## Introduction

Wonkey includes a simple build system that converts wonkey files to C++, compiles the C++ code, and links the resultant object files.

The build system allows you to import `*.wx` files and several types of non-Wonkey files into a project for compilation and/or linking. This is done using a system import directive:

`#!monkey #Import "<system_file>"`

...or a local import directive:

`#!monkey #Import "local_file"`

Import directives can appear any where in a Wonkey source file, but it's generally tidiest if they are placed at the top of the file.

## System Imports

System files are files that are generally provided with the compiler toolset, and that the compiler and/or linker are configured to find automatically.<br>
Wonkey recognizes the following system file types:

| System file type suffix | System file type|
|:------------------------|:----------------|
| .wx                     | Wonkey module.  |
| .o, .obj, .a, .lib      | Static library. |
| .so, .dll, .dylib       | Dynamic library.|
| .framework              | MacOS framework.|
| .h, .hh, .hpp           | C/C++/Objective C header.|

Note that system file names are enclosed by **`<`** and **`>`** characters, while local file names are not.

An example of importing a system library:

`#!monkey #Import "<wsock32.a>"`

If no extension is provided for a system import, Wonkey will assume you are importing a wonkey module, eg:

`#!monkey #Import "<std>"`

This will import the wonkey 'std' module. This is effectively the same as:

`#!monkey #Import "<std.wx>"`

## Local Imports

Local files are files that are located relative to the Wonkey file that imports them.

Wonkey recognizes the following local file types:

| Local file type suffix       | Local file type
|:-----------------------------|:---------------
| .wx                          | Wonkey source code.
| .o, .obj                     | Object file.
| .a, .lib                     | Static library.
| .so, .dll, .dylib            | Dynamic library.
| .framework                   | MacOS framework.
| .exe                         | Windows executable.
| .c, .cc, .cxx, .cpp, .m, .mm | C/C++/Objective C source code.
| .h, .hh, .hpp                | C/C++/Objective C header.

When importing *.wx files, the file extension can be omited:

`#!monkey #Import "player" ' imports player.wx`

## Import include directories

It is also possible to add local 'include directories', 'library directories' and 'framework directories' with import. This is done using syntax similar to a local import, but replacing the filename with a wildcard.

For example, to add an include directory:

`#!monkey #Import "include_directory/*.h"`

This will allow you to import any header file inside 'include\_directory' using...

`#!monkey #Import "<include_file>"`

...without having to specify the full path of the file.

To add a library directory:

`#!monkey #Import "staticlib_directory/*.a"`

To add a macOS framework directory:

`#!monkey #Import "framework_directory/*.framework"`

## Importing Assets

`#!monkey #Import` is also used for importing assets like images, sound files, etc.

See the topic about [Assets](assets.md) for detailed informations.
