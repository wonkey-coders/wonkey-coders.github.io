_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).DeleteDir_
##### Function DeleteDir:[Bool](../../modules/wonkey/wonkey-types-bool.md)( dir:[String](../../modules/wonkey/wonkey-types-string.md),recursive:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Deletes a directory at a filesystem path.

If `recursive` is true, all subdirectories are also deleted.

Returns true if successful.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path. |
| `recursive` | recursive True to delete subdirectories too. |
