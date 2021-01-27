_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawPrimitives_
##### Method DrawPrimitives:Void( order:[Int](../../modules/wonkey/wonkey-types-int.md),count:[Int](../../modules/wonkey/wonkey-types-int.md),vertices:[Float](../../modules/wonkey/wonkey-types-float.md) Ptr,verticesPitch:[Int](../../modules/wonkey/wonkey-types-int.md),texCoords:[Float](../../modules/wonkey/wonkey-types-float.md) Ptr,texCoordsPitch:[Int](../../modules/wonkey/wonkey-types-int.md),colors:[UInt](../../modules/wonkey/wonkey-types-uint.md) Ptr,colorsPitch:[Int](../../modules/wonkey/wonkey-types-int.md),image:[Image](../../modules/mojo/mojo-graphics-image.md),indices:[Int](../../modules/wonkey/wonkey-types-int.md) Ptr )
Draws a sequence of primtives.

Draws a sequence of convex primtives using the current [Color](mojo-graphics-canvas-color.md), [BlendMode](mojo-graphics-canvas-blendmode.md) and [Matrix](mojo-graphics-canvas-matrix.md).

| Parameters |    |
|:-----------|:---|
| `order` | order The type of primitive: 1=points, 2=lines, 3=triangles, 4=quads, >4=n-gons. |
| `count` | count The number of primitives to draw. |
| `vertices` | vertices Pointer to the first vertex x,y pair. |
| `verticesPitch` | verticesPitch Number of bytes from one vertex x,y pair to the next. Set to 8 for 'tightly packed' vertices. |
| `texCoords` | texCoords Pointer to the first texCoord s,t pair. This can be null. |
| `texCoordsPitch` | texCoordsPitch Number of bytes from one texCoord s,y to the next. Set to 8 for 'tightly packed' texCoords. |
| `colors` | colors Pointer to the first RGBA uint color value. This can be null. |
| `colorsPitch` | colorsPitch Number of bytes from one RGBA color to the next. Set to 4 for 'tightly packed' colors. |
| `image` | image Source image for rendering. This can be null. |
| `indices` | indices Pointer to sequence of integer indices for indexed drawing. This can by null for non-indexed drawing. |
