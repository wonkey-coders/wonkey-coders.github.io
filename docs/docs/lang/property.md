# Property

## Introduction

To declare a read/write property:

```monkey
Property Identifier : Type ()
    ...getter code...
Setter ( Identifier : Type )
    ...setter code...
End
```

To declare a read only property:

```monkey
Property Identifier : Type ()
    ...getter code...
End
```

To declare a write only property:

```monkey
Property ( Identifier : Type )
    ...setter code...
End
```
