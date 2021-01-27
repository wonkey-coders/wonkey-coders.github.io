_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[PbrMaterial](../../modules/mojo3d/mojo3d-pbrmaterial.md).New_
##### Method New:Void(  )
##### Method New:Void( color:[std.graphics.Color](../../modules/std/std-graphics-color.md),metalness:[Float](../../modules/wonkey/wonkey-types-float.md)=1.0,roughness:[Float](../../modules/wonkey/wonkey-types-float.md)=1.0 )
##### Method New:Void( material:[PbrMaterial](../../modules/mojo3d/mojo3d-pbrmaterial.md) )
Creates a new pbr material.

All properties default to white or '1' except for emissive factor which defaults to black.

If you set an emissive texture, you will also need to set emissive factor to white to 'enable' it.

The metalness value should be stored in the 'blue' channel of the metalness texture if the texture has multiple color channels.

The roughness value should be stored in the 'green' channel of the metalness texture if the texture has multiple color channels.

The occlusion value should be stored in the 'red' channel of the occlusion texture if the texture has multiple color channels.

The above last 3 rules allow you to pack metalness, roughness and occlusion into a single texture.
