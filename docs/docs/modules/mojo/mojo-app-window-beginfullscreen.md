_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[Window](../../modules/mojo/mojo-app-window.md).BeginFullscreen_
##### Method BeginFullscreen:Void(  )
##### Method BeginFullscreen:Void( width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md),hertz:[Int](../../modules/wonkey/wonkey-types-int.md) )
Switches window to fullscreen mode.

If called with no parameters, resizes the window to cover the entire desktop without actually changing the display mode.

If called with size and refresh rate parameters, both the display mode and window size are changed.

Changes display mode and switches to fullscreen mode.

The display resolution is changed, the window is resized and any window decorations are hidden.
