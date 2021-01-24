# Windows

## The 'Windows' Target

Wonkey can use either the mingw compiler or Microsoft Build Tools 2019 to build desktop apps.

To use mingw, you can use the mingw build tools at [github.com/wonkey-coders/wonkey](https://github.com/wonkey-coders/wonkey/).<br>
Simply download the mingw build tools package, run it (it's a self extracting exe), and select your 'Wonkey/devtools' dir for installation.

<!--
Note that the prebuilt binaries available from itch.io already include mingw in the 'devtools' dir.
-->

To use MS Build Tools 2019 instead of mingw, you will need to install MS Build Tools 2019 and change the following line in bin/windows/env_windows.txt:

```
#WX_USE_MSVC=1

WX_MSVC_DIR=${ProgramFiles(x86)}\Microsoft Visual Studio\2019\BuildTools\VC
WX_MSVC_TOOLS_DIR=${WX_MSVC_DIR}\Tools\MSVC\14.28.29333
WX_WINDOWS_KITS_DIR=${ProgramFiles(x86)}\Windows Kits\10
WX_WINDOWS_KIT=10.0.18362.0
```

You will need to rebuild all desktop modules after doing this.

Downloads for MS Build Tools 2019 can be found here: [MS Build Tools 2019](https://visualstudio.microsoft.com/thank-you-downloading-visual-studio/?sku=BuildTools&rel=16).
