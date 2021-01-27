_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).AddLight_
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sx:[Float](../../modules/wonkey/wonkey-types-float.md),sy:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddLight:Void( light:[Image](../../modules/mojo/mojo-graphics-image.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
Adds a light to the canvas.

This method must only be called while the canvas is in lighting mode, ie: between calls to [BeginLighting](mojo-graphics-canvas-beginlighting.md) and [EndLighting](mojo-graphics-canvas-endlighting.md).
