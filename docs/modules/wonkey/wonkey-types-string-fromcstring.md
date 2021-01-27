_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).FromCString_
##### Function FromCString:[String](../../modules/wonkey/wonkey-types-string.md)( buf:Void Ptr,bufSize:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Function FromCString:[String](../../modules/wonkey/wonkey-types-string.md)( buf:Void Ptr )
Creates a string from a CString.

If `bufSize` is specified, the CString may contain null characters which will be included in the string.

If `bufSize` is not specified, the CString must be correctly null terminated or Bad Things Will Happen.

| Parameters |    |
|:-----------|:---|
| `buf` | buf The memory buffer containing the CString. |
| `bufSize` | bufSize The size of the memory buffer in bytes. |
