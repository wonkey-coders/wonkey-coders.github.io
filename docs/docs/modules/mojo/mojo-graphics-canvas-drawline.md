_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawLine_
##### Method DrawLine:Void( x0:[Float](../../modules/wonkey/wonkey-types-float.md),y0:[Float](../../modules/wonkey/wonkey-types-float.md),x1:[Float](../../modules/wonkey/wonkey-types-float.md),y1:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method DrawLine:Void( v0:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),v1:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
Draws a line.

Draws a line in the current [Color](mojo-graphics-canvas-color.md) using the current [BlendMode](mojo-graphics-canvas-blendmode.md).

The line coordinates are transformed by the current [Matrix](mojo-graphics-canvas-matrix.md) and clipped to the current [Viewport](mojo-graphics-canvas-viewport.md) and [Scissor](mojo-graphics-canvas-scissor.md).

| Parameters |    |
|:-----------|:---|
| `x0` | x0 X coordinate of first endpoint of the line. |
| `y0` | y0 Y coordinate of first endpoint of the line. |
| `x1` | x1 X coordinate of first endpoint of the line. |
| `y1` | y1 Y coordinate of first endpoint of the line. |
| `v0` | v0 First endpoint of the line. |
| `v1` | v1 Second endpoint of the line. |
