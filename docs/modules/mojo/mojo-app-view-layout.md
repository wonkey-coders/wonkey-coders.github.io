_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).[View](../../modules/mojo/mojo-app-view.md).Layout_
##### Property Layout:[String](../../modules/wonkey/wonkey-types-string.md)
Layout mode.

The following layout modes are supported

| Layout mode		| Description
|:------------------|:-----------
| "fill"			| View is resized to fit its layout frame.
| "float"			| View floats within its layout frame according to the view [Gravity](mojo-app-view-gravity.md).
| "fill-x"			| View is resized on the x axis and floats on the y axis.
| "fill-y"			| View is resized on the y axis and floats on the x axis.
| "stretch"			| View is stretched non-uniformly to fit its layout frame.
| "letterbox"		| View is uniformly stretched on both axii and centered within its layout frame.
| "letterbox-int"	| View is uniformly stretched on both axii and centered within its layout frame. Scale factors are integrized.
