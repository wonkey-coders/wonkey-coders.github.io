# Conditional statements

## If

The **`If`** statement allows you to conditionally execute a block of statements depending on the result of a series of boolean expressions.

The first boolean expression that evaluates to true will cause the associated block of statements to be executed. No further boolean expressions will be evaluated.

If no boolean expression evaluates to True, then the final else block will be executed if present.

The syntax for the **`If`** statement is:

```
If expression [ Then ]

    Statements...

ElseIf expression [ Then ]

    Statements...

Else

    Statements...

EndIf
```

There may be any number of **`ElseIf`** blocks, or none. The final **`Else`** block is optional.

**`End`** or **`End If`** may be used instead of **`EndIf`**, and **`Else If`** may be used instead of **`ElseIf`**.

In addition, a simple one line version of **`If`** is also supported:

```
If Expression [ Then ] Statement [ Else Statement ]
```

## Select

The **`Select`** statement allows you to execute a block of statements depending on a series of comparisons.

The first comparison to produce a match will cause the associated block of statements to be executed.

If no comparisons produce a match, then the final **`Default`** block will be executed if present.

The syntax for the **`Select`** statement is:

```
Select Expression

    Case Expression [ , Expression... ]

        Statements...

    Default

        Statements...

End [ Select ]
```

There may be any number of **`Case`** blocks, or none. The final **`Default`** block is optional.
 If the default block is present, it must appear after all **`Case`** blocks.

## ? Else

The **`? Else`** operator is used to assign a value with a condition:

`variable = Expression ? Expression-A Else Expression-B`

The _variable_ will receive the value of _Expression-A_ if _Expression_ is True, else it will receive the value of _Expression-B_.

The following example:<br>
`i = j>2 ? 5 Else j+7`<br>
is the same as writing:
```monkey
If j>2
    i = 5
Else
    i = j+7
EndIf
```

## ?Else

The 'Elvis operator' **`?Else`** can be used to return an alternate value if an expression is null.

`variable = Expression ?Else Expression-B`

For example:

`r = x ?Else -1`

This will assign the value of **`x`** to **`r`** if **`x`** is non-null.<br>Otherwise it will assign the value **-1** to **`r`**.
