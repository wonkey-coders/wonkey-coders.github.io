_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).Mid_
##### Method Mid:[String](../../modules/wonkey/wonkey-types-string.md)( from:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md) )
Gets a substring from the middle of the string.

Returns a string consisting of `count` characters starting from index `from`.

If `count` is less than or equal to 0, an empty string is returned.

If `from`+`count` is greater than the length of the string, the returned string is truncated.

| Parameters |    |
|:-----------|:---|
| `from` | from The index of the first character to return. |
| `count` | count The number of characters to return. |
