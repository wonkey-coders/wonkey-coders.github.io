_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).CreateFile_
##### Function CreateFile:[Bool](../../modules/wonkey/wonkey-types-bool.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),createDir:[Bool](../../modules/wonkey/wonkey-types-bool.md)=true )
Creates a file at a filesystem path.

Any existing file at the path will be overwritten.

Returns true if successful.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path of the file file to create. |
| `createDir` | createDir If true, also creates the file directory if necessary. |
