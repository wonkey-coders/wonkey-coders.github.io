_[mojox](../../modules/mojox/mojox-module.md):[mojox](../../modules/mojox/mojox-module.md).[DockingView](../../modules/mojox/mojox-dockingview.md).AddView_
##### Method AddView:Void( view:[mojo.app.View](../../modules/mojo/mojo-app-view.md),location:[String](../../modules/wonkey/wonkey-types-string.md) )
##### Method AddView:Void( view:[mojo.app.View](../../modules/mojo/mojo-app-view.md),location:[String](../../modules/wonkey/wonkey-types-string.md),size:[String](../../modules/wonkey/wonkey-types-string.md) )
##### Method AddView:Void( view:[mojo.app.View](../../modules/mojo/mojo-app-view.md),location:[String](../../modules/wonkey/wonkey-types-string.md),size:[String](../../modules/wonkey/wonkey-types-string.md),resizable:[Bool](../../modules/wonkey/wonkey-types-bool.md) )
Adds a view.

`location` should be one of "left", "right", "top", "bottom".

`size` can be either an integer number of pixels or a percentage. If no size is specified, the view's layout size is used.

If `resizable` is true, the view can be resizable. Note: this must be used with `size` set to a non-0 integer.
