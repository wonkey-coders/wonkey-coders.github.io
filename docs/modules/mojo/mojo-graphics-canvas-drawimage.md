_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawImage_
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sx:[Float](../../modules/wonkey/wonkey-types-float.md),sy:[Float](../../modules/wonkey/wonkey-types-float.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method DrawImage:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
Draws an image.
Draws an image using the current [Color](mojo-graphics-canvas-color.md), [BlendMode](mojo-graphics-canvas-blendmode.md) and [Matrix](mojo-graphics-canvas-matrix.md).

| Parameters |    |
|:-----------|:---|
| `tx` | tx X coordinate to draw image at. |
| `ty` | ty Y coordinate to draw image at. |
| `tv` | tv X/Y coordinates to draw image at. |
| `rz` | rz Rotation angle, in radians, for drawing. |
| `sx` | sx X axis scale factor for drawing. |
| `sy` | sy Y axis scale factor for drawing. |
| `sv` | sv X/Y scale factor for drawing. |
