_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).OpenCFile_
##### Function OpenCFile:[libc.FILE](../../modules/libc/libc-file.md) Ptr( path:[String](../../modules/wonkey/wonkey-types-string.md),mode:[String](../../modules/wonkey/wonkey-types-string.md) )
Opens a 'C' file.

Opens a file that can be used with the 'C' calls fopen, fread, fwrite and fclose. Similar to plain libc.fopen, except that it can also handle assets on android.

`mode` should be one of: "r", "w" or "rw". When opening a file using "r" or "rw", the file must already exist or the function will fail and null will be returned. When opening a file using "w", any existing file at the same path will be overwritten.
