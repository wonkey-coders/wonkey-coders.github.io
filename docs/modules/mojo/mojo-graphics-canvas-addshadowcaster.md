_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).AddShadowCaster_
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sx:[Float](../../modules/wonkey/wonkey-types-float.md),sy:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md) )
##### Method AddShadowCaster:Void( caster:[ShadowCaster](../../modules/mojo/mojo-graphics-shadowcaster.md),tv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md),rz:[Float](../../modules/wonkey/wonkey-types-float.md),sv:[std.geom.Vec2f](../../modules/std/std-geom-vec2f.md) )
Adds a shadow caster to the canvas.

This method must only be called while the canvas is in lighting mode, ie: between calls to [BeginLighting](mojo-graphics-canvas-beginlighting.md) and [EndLighting](mojo-graphics-canvas-endlighting.md).
