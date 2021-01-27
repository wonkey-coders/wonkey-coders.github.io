_[std](../../modules/std/std-module.md):[std.memory](../../modules/std/std-memory.md).[DataBuffer](../../modules/std/std-memory-databuffer.md).Compress_
##### Method Compress:[DataBuffer](../../modules/std/std-memory-databuffer.md)( compressionLevel:[Int](../../modules/wonkey/wonkey-types-int.md)=-1 )
Compresses data buffer.

The `compressionLevel` parameter should be a value from 0 to 9 (inclusive), or -1 for default compression (currently 6).

A compreesion level of 1 gives best speed, 9 gives best compression.

This method prepends an 8 byte 'header' to the returned data.
