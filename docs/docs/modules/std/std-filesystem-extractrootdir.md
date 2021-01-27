_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).ExtractRootDir_
##### Function ExtractRootDir:[String](../../modules/wonkey/wonkey-types-string.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Extracts the root directory from a file system path.

A root directory is a directory path that:

* Starts with '//' or '/', or...

* Starts with 'blah:/', 'blah://' or 'blah::'.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path. |
