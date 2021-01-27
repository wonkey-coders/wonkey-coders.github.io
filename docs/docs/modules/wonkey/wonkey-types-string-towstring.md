_[wonkey](../../modules/wonkey/wonkey-module.md):[wonkey.types](../../modules/wonkey/wonkey-types.md).[String](../../modules/wonkey/wonkey-types-string.md).ToWString_
##### Method ToWString:Void( buf:Void Ptr,bufSize:[Int](../../modules/wonkey/wonkey-types-int.md) )
Converts the string to a WString.

If there is enough room in the memory buffer, a null terminating '0' is appended to the WString.

| Parameters |    |
|:-----------|:---|
| `buf` | buf Memory buffer to write the WString to. |
| `bufSize` | bufSize Size of the memory buffer in bytes. |
