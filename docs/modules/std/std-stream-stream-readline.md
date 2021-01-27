_[std](../../modules/std/std-module.md):[std.stream](../../modules/std/std-stream.md).[Stream](../../modules/std/std-stream-stream.md).ReadLine_
##### Method ReadLine:[String](../../modules/wonkey/wonkey-types-string.md)(  )
Reads a line of text from the stream.

Bytes are read from the stream until a newline character (ascii code 10) or null character (ascii code 0) is read, or end of file is detected.

The bytes read are returned in the form of a string, excluding any terminating newline or null character.

Carriage return characters (ascii code 13) are silently ignored.
