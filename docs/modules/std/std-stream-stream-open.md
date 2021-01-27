_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).Open_
##### Function Open:[Stream](../../modules/std/std-stream-stream.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),mode:[String](../../modules/wonkey/wonkey-types-string.md) )
Opens a stream

`mode` should be "r" for read, "w" for write or "rw" for read/write.

If the stream could not be opened, null will be returned.

When opening a file using "r" or "rw", the file must already exist or the function will fail and null will be returned.

When opening a file using "w", any existing file at the same path will be overwritten.

Stream paths may include the following prefixes:

| Stream path prefix	| Supported targets | Description
|:----------------------|:------------------|:-----------
| `asset::`				| All				| Open a stream for reading an app asset.
| `internal::`			| Mobile			| Open a stream for reading/writing internal app storage.
| `external::`			| Android			| Open a stream for reading/writing external app storage.
| `home::`				| Desktop 			| Open a stream for reading/writing a file in the user's home directory.
| `desktop::`			| Desktop 			| Open a stream for reading/writing a file in the user's desktop directory.

| Parameters |    |
|:-----------|:---|
| `mode` | mode The mode to open the stream in: "r", "w" or "rw" |
