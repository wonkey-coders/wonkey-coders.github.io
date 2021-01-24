
# Android

## The 'Android' Target

Wonkey uses the android NDK (native development kit) to build android apps.

## Setting up for Android development

1. Install Android Studio and make sure it works, ie: you can build and run one of
 the simple template projects on a device or emulator.<br/>
Android Studio is available here: [Android Studio](https://developer.android.com/studio/index.html).

2. Install the 'NDK' (native development kit) using Android Studio via 'SDK Manager->SDK Tools'.

3. Install the Android 7.0 (Nougat) SDK Platform (API Level 24) using Android Studio via 'SDK Manager'.

4. Edit your Wonkey **`bin/windows/env_windows.txt`** file and change the ndk-bundle 'PATH' setting so it points to the NDK. Or, you can just add the ndk-bundle directory to your system PATH.<br>
Please note: Use the file **`bin/macos/env_macos.txt`** on macOS and **`bin/linux/env_linux.txt`** on Linux.

1. Fire up the Wide IDE and select 'Build -> Update/Rebuild Modules -> Android'.<br>
Alternatively you can (re-)build the android modules on the command-line:<br>
**`wake mods -clean -target=android -config=debug`**<br>
**`wake mods -clean -target=android -config=release`**

## Building an Android app

1. Build your app in Wide using 'Build -> Build Only' with 'Build Target -> Android' selected.

2. Open the generated Android Studio project (at myapp.products/Android) in Android Studio.

!!! Attention
    I recommend *disabling* the following Android Studio setting for Wonkey development:<br>
    **File -> Settings -> Build, Execution, Deployment -> Instant Run -> Enable Instant Run**<br>
    With this enabled, Android Studio doesn't seem to notice when external project files change.
