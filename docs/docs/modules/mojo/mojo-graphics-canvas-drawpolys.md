_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawPolys_
##### Method DrawPolys:Void( order:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md),vertices:[Float](../../modules/wonkey/wonkey-types-float.md)[] )
Draws a sequence of polygons.

Draws a sequence of polygons using the current [Color](mojo-graphics-canvas-color.md), [BlendMode](mojo-graphics-canvas-blendmode.md) and [Matrix](mojo-graphics-canvas-matrix.md).

| Parameters |    |
|:-----------|:---|
| `order` | order The type of polygon: 3=triangles, 4=quads, >4=n-gons. |
| `count` | count The number of polygons. |
| `vertices` | vertices Array of x/y vertex coordinate pairs. |
