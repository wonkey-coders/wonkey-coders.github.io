_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).ExtractDir_
##### Function ExtractDir:[String](../../modules/wonkey/wonkey-types-string.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Extracts the directory component from a filesystem path.

If `path` is a root directory it is returned without modification.

If `path` does not contain a directory component, an empty string is returned.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path. |
