
# Built-in data types

## Primitive types

The following primtive types are supported:

| Type Name	 | Description                  | Storage Size | Range (Dec)             |
|:-----------|:-----------------------------|:------------:|:-----------------------:|
| **Void**   | No type.                     | -            | -                       |
| **Bool**   | Boolean type.                | ?            | '0' or '<> 0'<br/>**True** or **False**   |
| **Byte**   | 8 bit signed integer.        | 1 Byte       | -128 - 127              |
| **UByte**  | 8 bit unsigned integer.      | 1 Byte       | 0 - 255                 |
| **Short**  | 16 bit signed integer.       | 2 Bytes      | -32.768 - 32.767          |
| **UShort** | 16 bit unsigned integer.     | 2 Bytes      | 0 - 65.535               |
| **Int**    | 32 bit signed integer.       | 4 Bytes      | -2.147.483.648 - 2.147.483.647
| **UInt**   | 32 bit unsigned integer.     | 4 Bytes      | 0 - 4.294.967.295       |
| **Long**   | 64 bit signed integer.       | 8 Bytes      | -9.223.372.036.854.775.808 - 9.223.372.036.854.775.807
| **ULong**  | 64 bit unsigned integer.     | 8 Bytes      | 0 - 18.446.744.073.709.551.615
| **Float**  | 32 bit floating point.       | 4 Bytes      | 1.2E-38 - 3.4E+38<br>(Precision: 6 decimal places)
| **Double** | 64 bit floating point.       | 8 Bytes      | 2.3E-308 - 1.7E+308<br>(Precision: 15 decimal places)
| **String** | String of 16 bit characters. | 2 Bytes<br>(each char) | 0 - 65.535<br>(each char)
| **Object** | Base type of all objects.    | -                       | -


## Compound types

The following compound types are supported:

| Type Syntax							| Description
|:--------------------------------------|:-----------
| _ElementType_ **[]**						| Array type.
| _PointeeType_ **Ptr**					| Pointer type.
| _ReturnType_ **(** _ParameterTypes_ **)**	| Function type.

Array types can have more than one dimension, for example: **`[,]`** declares a 2D array, **`[,,]`** declares a 3D array and so on.

The parameter types for a function type can optionally include an identifier prefix, for example: `MyFunction:Int( arg:Int )`. The prefix must be a valid identifier but is otherwise ignored.

## Implicit type conversions

These type conversions are performed automatically:

| Source type						| Destination type
|:----------------------------------|:-----------------
| **Bool**							| **String**
| Any numeric type					| **Bool**, **String** or any numeric type.
| **String** or any array type 		| **Bool**
| Any pointer type					| **Void Ptr**
| Class, interface or struct type	| **Bool**
| Class or interface type			| Base class or implemented interface type
| Enum type							| **Bool** or any integral type.

When numeric values are converted to bool, the result will be true if the value is not equal to 0.

When strings and arrays are converted to bool, the result will be true if the length of the string or array is not 0.

When class or interface instances are converted to bool, the result will be true if the instance is not equal to null.

When struct values are converted to bool, the result will be true if the struct value is not equal to null.

When floating point values are converted to integral values, the fractional part of the floating point value is chopped off - no rounding is performed.

When bools are converted to strings, the result will be either "True" or "False".


## Explicit type conversions 

Some type conversions must be explicitly performed using the 'cast' operator. The cast operator has the syntax:

`Cast<DestinationType>(SourceExpression)`

You must use the cast operator to perform the following type conversions:

| Source type			| Destination type
|:----------------------|:-----------------
| **Bool**				| Any numeric type
| **String**				| Any numeric type
| Any pointer type		| Any pointer type or any integral type
| Any integral type		| Any pointer type or any enum type.
| Class type			| Derived class or any interface type.
| Interface type		| Any class or interface type.

When using the cast operator to dynamically downcast an object or interface instance, the result will be **`Null`** if the cast failed.

When casting bool values to a numeric type, the result will be 1 for true, 0 for false.

You can also use 'function syntax' to explictly cast values to primitive types:

```monkey
Local floatValue:Float = 3.14
Local intValue := Int( floatValue )
```
