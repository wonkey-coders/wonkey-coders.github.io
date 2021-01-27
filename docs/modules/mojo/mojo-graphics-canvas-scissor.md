_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).Scissor_
##### Property Scissor:[std.geom.Recti](../../modules/std/std-geom-recti.md)
The current scissor rect.

The scissor rect is a rect within the viewport that can be used for additional clipping.

Scissor rect coordinates are relative to the current viewport rect, but are not affected by the current drawing matrix.

This property must not be modified if the canvas is in lighting mode.
