_[std](../../modules/std/std-module.md):[std.stringio](../../modules/std/std-stringio.md).LoadString_
##### Function LoadString:[String](../../modules/wonkey/wonkey-types-string.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),fixeols:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Loads a string from a file.

An empty string will be returned if the file could not be opened.

| Parameters |    |
|:-----------|:---|
| `path` | path The path of the file. |
| `fixeols` | fixeols If true, converts eols to UNIX "~n" eols after loading. |
