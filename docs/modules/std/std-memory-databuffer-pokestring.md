_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).PokeString_
##### Method PokeString:Void( offset:[Int](../../modules/wonkey/wonkey-types-int.md),value:[String](../../modules/wonkey/wonkey-types-string.md) )
Write a string to the databuffer.

If there is not enough room in the data buffer, the string data is truncated.

The string is written in utf8 format, but no null terminator is written. Use [PokeCString](std-memory-databuffer-pokecstring.md) to write a null terminated string.

| Parameters |    |
|:-----------|:---|
| `offset` | offset Byte offset to write the string. |
| `value` | value The string to write. |
