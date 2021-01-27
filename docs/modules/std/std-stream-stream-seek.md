_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).Seek_
##### Method Seek:Void( position:[Int](../../modules/wonkey/wonkey-types-int.md) )
Seeks to a position in the stream.

In debug builds, a runtime error will occur if the stream is not seekable or `position` is out of range.

| Parameters |    |
|:-----------|:---|
| `position` | position The position to seek to. |
