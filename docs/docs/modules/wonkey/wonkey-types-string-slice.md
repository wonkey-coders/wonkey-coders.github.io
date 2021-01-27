_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).Slice_
##### Method Slice:[String](../../modules/wonkey/wonkey-types-string.md)( from:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method Slice:[String](../../modules/wonkey/wonkey-types-string.md)( from:[Int](../../modules/wonkey/wonkey-types-int.md),tail:[Int](../../modules/wonkey/wonkey-types-int.md) )
Extracts a substring from the string.

Returns a string consisting of all characters from `from` until (but not including) `tail`, or until the end of the string if `tail`
is not specified.

If either `from` or `tail` is negative, it represents an offset from the end of the string.

| Parameters |    |
|:-----------|:---|
| ``from`` | `from` The starting index. |
| ``tail`` | `tail` The ending index. |
