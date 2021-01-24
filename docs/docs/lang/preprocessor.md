# The Preprocessor

## Introduction

Wonkey includes a simple preprocessor that allows you to conditionally compile code depending on a number of build setttings.

The preprocessor supports the following statements: #Import, #If, #Else, #ElseIf, #EndIf, #Rem, #End. Preprocessor statements must begin on a new line.

## \#Import

For **`#Import`** see the topic [Imports](import.md).

## \#Rem .. \#End

For block comments using **`#Rem`** and **`#End`** see the topic [Comments](comments.md).

## \#If .. \#Else .. \#ElseIf .. \#EndIf

Preprocessor expressions may only use the 'And', 'Or' and comparison operators.

The following symbols may be used in preprocessor expressions:

| Symbol                  | Type   | Meaning
|:------------------------|:-------|:--------------------------------------------
| \_\_TARGET\_\_          | String | The current build target. One of:<br>"windows", "macos", "linux", "raspberry",<br>"android", "ios", "emscripten"
| \_\_CONFIG\_\_          | String | The current build config. One of: "release", "debug"
| \_\_DESKTOP\_TARGET\_\_ | Bool   | True if the current build target is windows, macos or linux.
| \_\_MOBILE\_TARGET\_\_  | Bool   | True if the current build target is android or ios.
| \_\_WEB\_TARGET\_\_     | Bool   | True if the current build target is emscripten.
| \_\_DEBUG\_\_           | Bool   | True if the current build config is debug.
| \_\_RELEASE\_\_         | Bool   | True if the current build config is release.

For example, to include code in debug builds only, use something like:

```monkey
#If __DEBUG__
    Print "This code is only included in debug builds."
#Endif
```

To include code on desktop or mobile builds, use:

```monkey
#If __DESKTOP_TARGET__ Or __MOBILE_TARGET__
    Print "This code is only include in desktop and mobile builds."
#Endif
```
