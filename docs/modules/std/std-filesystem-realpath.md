_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).RealPath_
##### Function RealPath:[String](../../modules/wonkey/wonkey-types-string.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Converts a path to a real path.

If `path` is a relative path, it is first converted into an absolute path by prefixing the current directory.

Then, any internal './' or '../' references in the path are collapsed.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path. |
