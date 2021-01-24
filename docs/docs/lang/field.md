# Field

## Introduction

Fields are variables that live inside the memory allocated for an instance of a class or struct. To declare a field variable:

```monkey
Field identifier : Type [ = Expression ]
```

...or...

```monkey
Field identifier := Expression
```

For struct fields, _Expression_ must not contain any code that has side effects.
