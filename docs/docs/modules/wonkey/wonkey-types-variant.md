_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).Variant_
##### Struct Variant
Variant type.

The 'Variant' type is a primitive type that can be used to 'box' values of any type.

An uninitialized variant will contain a 'null' value (of type Void) until you assign something to it.

A variant is 'true' if it contains any value with a non-void type (including a bool false value!) and 'false' if it is uninitialized and has no (void) type.

Any type of value can be implicitly converted to a variant.

To retrieve the value contained in a variant, you must explicitly cast the variant to the desired type. Note that the cast must specify the exact type of the value already contained in the variant, or a runtime error will occur.

The one exception to this is if the variant contains a class object, in which case you can cast the variant to any valid base class of the object.

| Properties | |
|:---|:---|
| [DynamicType](wonkey-types-variant-dynamictype.md) | Dynamic type of the variant value. _(read only)_ |
| [EnumValue](wonkey-types-variant-enumvalue.md) | Gets the integer enum value of an enum variant. _(read only)_ |
| [Type](wonkey-types-variant-type.md) | Static Type of the variant value. _(read only)_ |

| Methods | |
|:---|:---|
| [GetArrayElement](wonkey-types-variant-getarrayelement.md) | Gets an element from an array. |
| [GetArrayLength](wonkey-types-variant-getarraylength.md) | Gets the length of an array. |
| [SetArrayElement](wonkey-types-variant-setarrayelement.md) | Sets an element of an array. |
