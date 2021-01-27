_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).StripDir_
##### Function StripDir:[String](../../modules/wonkey/wonkey-types-string.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Strips the directory component from a filesystem path.

If `path` is a root directory an empty string is returned.

If `path` does not contain a directory component, `path` is returned without modification.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path. |
