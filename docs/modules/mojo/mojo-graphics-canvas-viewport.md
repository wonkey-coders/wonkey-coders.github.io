_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).Viewport_
##### Property Viewport:[std.geom.Recti](../../modules/std/std-geom-recti.md)
The current viewport.

The viewport describes the rect within the render target that rendering occurs in.

All rendering is relative to the top-left of the viewport, and is clipped to the intersection of the viewport and scissor rects.

This property must not be modified if the canvas is in lighting mode.
