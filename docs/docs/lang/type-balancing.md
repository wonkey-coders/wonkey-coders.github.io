# Type balancing

## Introduction

When evaluating an operator's operands, it is sometimes necessary to adjust the type of one or both operands.

When evaluating the operands of arithemetic or comparison operators, the following rules are used:

* If either operator is String, the other is converted to String.
* Else If either operand is Double, the other is converted to Double.
* Else if either operand is Float, the other is converted to Float.
* Else if either operand is ULong, the other is converted to ULong.
* Else if either operand is Long, the other is converted to Long.
* Else if either operand is unsigned, both are converted to UInt.
* Else both operands are converted to Int.

When evaluating the operands of the **`&`**, **`|`** and **`^`** integer operators, both operands must be integral types and are converted as follows:

* If either operand is ULong, the other is converted to ULong.
* Else if either operand is Long, the other is converted to Long.
* Else if either operand is unsigned, both are converted to UInt.
* Else both operands are converted to Int.

When evaluating the operand of the **`Shl`** and **`Shr`** integer operators, the left-hand-side must be an integral type, while the right-hand-side 'shift amount' operand is converted to Int.
