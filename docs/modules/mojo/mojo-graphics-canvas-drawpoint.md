_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawPoint_
##### Method DrawPoint:Void( x:[Float](../../modules/wonkey/wonkey-types-float.md),y:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method DrawPoint:Void( v:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
Draws a point.

Draws a point in the current [Color](mojo-graphics-canvas-color.md) using the current [BlendMode](mojo-graphics-canvas-blendmode.md).

The point coordinates are transformed by the current [Matrix](mojo-graphics-canvas-matrix.md) and clipped to the current [Viewport](mojo-graphics-canvas-viewport.md) and [Scissor](mojo-graphics-canvas-scissor.md).

| Parameters |    |
|:-----------|:---|
| `x` | x Point x coordinate. |
| `y` | y Point y coordinate. |
| `v` | v Point coordinates. |
