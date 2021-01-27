_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[View](../../modules/mojo/mojo-app-view.md).AddChildView_
##### Method AddChildView:Void( view:[View](../../modules/mojo/mojo-app-view.md) )
Adds a child view to this view.

AddChildView is normally used internally by 'layout' views. However you can also add a child view to any view directly by calling this method.

If you use this method to add a child view to a view, it is your responsiblity to also manage the child view's frame using the [Frame](mojo-app-view-frame.md) property.
