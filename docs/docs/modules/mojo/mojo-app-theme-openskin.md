_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[Theme](../../modules/mojo/mojo-app-theme.md).OpenSkin_
##### Method OpenSkin:[Skin](../../modules/mojo/mojo-app-skin.md)( path:[String](../../modules/wonkey/wonkey-types-string.md) )
Loads a skin from a file.

If `file` is an absolute path, this method is effectively the same as calling [Skin.Load](mojo-app-theme-skin.load.md).

If `file` is not an absolute path, the skin is searched for in the following locations:

* The theme directory.

* The asset::images/ directory.
