_[std](../../modules/std/std-module.md):[std.filesystem](../../modules/std/std-filesystem.md).CreateDir_
##### Function CreateDir:[Bool](../../modules/wonkey/wonkey-types-bool.md)( dir:[String](../../modules/wonkey/wonkey-types-string.md),recursive:[Bool](../../modules/wonkey/wonkey-types-bool.md)=true,clean:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Creates a directory at a filesystem path.

| Parameters |    |
|:-----------|:---|
| `path` | path The filesystem path of the directory to create. |
| `recursive` | recursive If true, any required parent directories are also created. |
| `clean` | clean If true, any existing directory at `dir` is first deleted. |
