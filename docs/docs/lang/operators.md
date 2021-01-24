# Operators

## Introduction

## Operator precedence

| Operator			| Description					| Precedence
|:------------------|:------------------------------|:--------------
| `New`				| New object or array			| 1
| `Null`			| Null value					|
| `Self`			| Self instance					|
| `Super`			| Super instance				|
| `True`			| Boolean true					|
| `False`			| Boolean false					|
| `Typeof`			| Typeof operator				|
| `Cast`			| Cast operator					|
| `Lambda`			| Lambda function				|
| _identifier_		| Identifier					|
| _literal_			| Literal value					|
| | |
| `?.`				| Safe postfix member access 	| 2
| `.`				| Postfix member acccess		| 
| `( )`				| Postfix Invoke				|
| `[ ]`				| Postfix Index					|
| `< >`				| Postfix Generic instance		|
| | |
| `Varptr`			| Unary variable address		| 3
| `-`				| Unary numeric negate			| 
| `~`				| Unary integer complement 		|
| `Not`				| Unary boolean invert			|
| | |
| `*`				| Numeric multiplication		| 4
| `/`				| Numeric division				|
| `Mod`				| Numeric modulo				|
| | |
| `+`				| Numeric addition				| 5
| `-`				| Numeric subtraction			|
| | |
| `Shl`				| Integer shift left			| 6
| `Shr`				| Integer shift right			|
| | |
| `&`				| Integer and					| 7
| `~`				| Integer xor					|
| | |
| `\|`				| Integer or					| 8
| | |
| `<=>`				| Compare						| 9
| | |
| `<`				| Less than						| 10
| `>`				| Greater than					|
| `<=`				| Less than or equal			|
| `>=`				| Greater than or equal			|
| | |
| `=`				| Equal							| 11
| `<>`				| Not equal						|
| | |
| `And`				| Boolean and					| 12
| | |
| `Or`				| Boolean or					| 13
| | |
| `?` `Else`		| If-then-else					| 14
| `?Else`			| 'Elvis operator' 				|

The safe member access operator allows you to safely access members of a possibly null object. Accessing a field, property or method of a null object using the plain '.' operator will cause a 'null object runtime error' in debug mode - in release it will likely just crash the program. However, using '?.' instead will cause a null value of the expected type to be returned instead, preventing the runtime error occuring. Note however that this involves some overhead as it means the object must be checked before it is accessed.

The 'Elvis operator' is a binary operator that returns its left hand argument if it is non-null, otherwise it returns its right hand argument. It is similar to 'X<>Null ? X Else Null' except that 'X' is only evaluted once.
