_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[Theme](../../modules/mojo/mojo-app-theme.md).OpenFont_
##### Method OpenFont:[Font](../../modules/mojo/mojo-graphics-font.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),size:[Float](../../modules/wonkey/wonkey-types-float.md) )
Loads a font from a file.

If `file` is an absolute path, this method is effectively the same as calling [Font.Load](mojo-app-theme-font.load.md).

If `file` is not an absolute path, the font is searched for in the following locations:

* The theme's directory.

* The asset::fonts/ directory.
