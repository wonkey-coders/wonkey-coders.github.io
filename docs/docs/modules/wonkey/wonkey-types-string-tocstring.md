_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).ToCString_
##### Method ToCString:Void( buf:Void Ptr,bufSize:[Int](../../modules/wonkey/wonkey-types-int.md) )
Converts the string to a CString.

If there is enough room in the memory buffer, a null terminating '0' is appended to the CString.

| Parameters |    |
|:-----------|:---|
| `buf` | buf Memory buffer to write the CString to. |
| `bufSize` | bufSize Size of the memory buffer in bytes. |
