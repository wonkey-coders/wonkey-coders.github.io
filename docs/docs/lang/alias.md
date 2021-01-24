# Alias

## Introduction

An **`Alias`** allows you to create a synonym for a previously declared type.

```monkey
Alias Identifier : Type
```

You can use your newly declared **`Alias`** instead of the original type anywhere in your code. For example:

```monkey
Alias FantasticNumber:Int
Alias FantasticString:String

Local myInt:FantasticNumber = 123
Local myString:FantasticString = "abc"
```
