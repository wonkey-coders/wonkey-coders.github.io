_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).FromWString_
##### Function FromWString:[String](../../modules/wonkey/wonkey-types-string.md)( buf:Void Ptr,bufSize:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Function FromWString:[String](../../modules/wonkey/wonkey-types-string.md)( buf:Void Ptr )
Creates a string from a null terminated WString.

If `bufSize` is specified, the WString may contain null characters which will be included in the string.

If `bufSize` is not specified, the WString must be correctly null terminated or Bad Things Will Happen.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer containing the WString. |
| `bufSize` | bufSize The size of the memory buffer in bytes. |
