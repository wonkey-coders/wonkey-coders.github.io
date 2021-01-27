_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[PbrMaterial](../../modules/mojo3d/mojo3d-pbrmaterial.md).Load_
##### Function Load:[PbrMaterial](../../modules/mojo3d/mojo3d-pbrmaterial.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),textureFlags:[mojo.graphics.TextureFlags](../../modules/mojo/mojo-graphics-textureflags.md)=(TextureFlags.WrapST|TextureFlags.FilterMipmap) )
Loads a PbrMaterial from a 'file'.

A .pbr file is actually a directory containing a number of textures in png format. These textures are:

color.png (required)
emissive.png
metalness.png
roughness.png
occlusion.png
normal.png
