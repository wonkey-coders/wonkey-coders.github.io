# Comments

## Line comments

Line comments can be added using the **'** character (ASCII-Code: 39, Hex: $27).<br>
Everything to the right of a single quote (**'**), until the end of a line, will be interpreted as a comment.
 Comments will be ignored during compilation time.
<!--
Everything after **'** is ignored by the compiler until the end of the line is reached.
-->

```monkey
'
' Example showing line comments
'
Print "hello!"    ' this is a line comment
```

## Block comments

Multiline comments can be made by using the **`#Rem`** and **`#End`** preprocessor directives.

**`#Rem`** initiates a block-comment and **`#End`** ends the block.

**`#Rem`** and **`#End`** both need to be at the start of the line. They can not be used within code lines.

```monkey
#Rem

    This is a multi-line block comment in Wonkey.

#End
Function Main()
    Print "Using #Rem..#End you can write block comments!"
End
```

<!--
See [[language-reference.preprocessor|preprocessor]]
-->

## Wonkeydoc

**`#Rem`** and **`#End`** can also be used for documentation of source-code. This is especially useful for documenting modules/libraries.

* A 'wonkeydoc' comment starts with **`#Rem wonkeydoc`** and ends with **`#End`**.
* Directly after 'wonkeydoc' follows the short description. The short description ends with the current line:

```monkey
#Rem wonkeydoc Add two integer numbers

    ...Detailed description...

#End
Function Add:Int( a:Int, b:Int )
    Return a + b
End
```

Directly after the wonkeydoc-block follows the entity to be documented.

Wonkeydoc can be used with:

* Namespaces (currently ignored)
* Interfaces, Classes, Structs, Enums
* Functions, Methods, Properties, Fields
* Aliases, Consts

### Detailed description

In the detailed description you can use the following special Wonkeydoc entities, each on a separate line:

* **`@param name description`** - used for documenting function/method parameters
* **`@return description`** - used for describing what a function/method returns.
* **`@example`** .. **`@end`** - Used for inserting multi-line examples into the docs.

### Markdown

You can use Markdown syntax for wonkeydoc:

* \` is used for code blocks
* \* creates lists

### Including tables

You can create tables using the usual Markdown syntax:

```markdown
| Header Cell 1   | Header Cell 2   | Header Cell 3
|:----------------|:----------------|:---------------
| Row 1, Column 1 | Row 1, Column 2 | Row 1, Column 3
| Row 2, Column 1 | Row 2, Column 2 | Row 2, Column 3
| Row 3, Column 1 | Row 3, Column 2 | Row 3, Column 3
```

### Links

You can use links to other wonkeydocs. Links are enclosed in **`[[`** and **`]]`**. An optional title can be set after a '|' character:

```
[[ link | Title ]]
```

To create a link to another function in the same file you simply use the name of the function:

```
[[FunctionName]]
```

To create a link to a class in another module you use the module name and the full name of the entity, including the namespace:

```
[[mojo:mojo.app.AppInstance|mojo.AppInstance]]

[[mojo3d:mojo3d.Renderer|mojo3d.Renderer]]
```

The part after the '|' character is the text that is displayed for the link.

### Wonkeydoc for overloaded functions/methods

Overloaded functions are not documented separately.
 Wonkeydoc is written for the first of the overloaded functions/methods and all '@params' are included in this one wonkeydoc.

Example:

```monkey
#Rem wonkeydoc Shows a message box

The message box is opened in modal mode and the user
needs to confirm it by pressing the 'OK' button.

@example
MsgBox("Get ready!")
MsgBox(10,10,"Oh no, you lost!")
@end

@param x the x-position for the window

@param y the y-position for the window

@param msg The message for the dialog window

@return This function does not return a value

#End
Function MsgBox( x:Int, y:Int, msg:String )
End

Function MsgBox( msg:String )
End
```

### Deprecated docs

Deprecated wonkeydoc is marked with `@deprecated`:

```monkey
#Rem wonkeydoc @deprecated
#End
Function old_func()
End
```

### Hidden docs

To skip the documentation of an entity you can use the short description `@hidden`:

```monkey
#Rem wonkeydoc @hidden

    This is not included in the documentation.

#End
Function xample()
End
```
