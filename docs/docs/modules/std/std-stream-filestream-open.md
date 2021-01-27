_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[FileStream](../../modules/std/std-stream-filestream.md).Open_
##### Function Open:[FileStream](../../modules/std/std-stream-filestream.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),mode:[String](../../modules/wonkey/wonkey-types-string.md) )
Opens a file and returns a new filestream.

When opening a file using "r" or "rw", the file must already exist or the function will fail and null will be returned.

When opening a file using "w", any existing file at the same path will be overwritten.

| Parameters |    |
|:-----------|:---|
| `path` | path The path of the file to open. |
| `mode` | mode The mode to open the file in: "r", "w" or "rw". |
