_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Image](../../modules/mojo/mojo-graphics-image.md).New_
##### Method New:Void( pixmap:[std.graphics.Pixmap](../../modules/std/std-graphics-pixmap.md),textureFlags:[TextureFlags](../../modules/mojo/mojo-graphics-textureflags.md)=TextureFlags.FilterMipmap,shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method New:Void( texture:[Texture](../../modules/mojo/mojo-graphics-texture.md),rect:[std.geom.Recti](../../modules/std/std-geom-recti.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method New:Void( texture:[Texture](../../modules/mojo/mojo-graphics-texture.md),shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method New:Void( atlas:[Image](../../modules/mojo/mojo-graphics-image.md),x:[Int](../../modules/wonkey/wonkey-types-int.md),y:[Int](../../modules/wonkey/wonkey-types-int.md),width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md) )
##### Method New:Void( atlas:[Image](../../modules/mojo/mojo-graphics-image.md),rect:[std.geom.Recti](../../modules/std/std-geom-recti.md) )
##### Method New:Void( width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md),format:[std.graphics.PixelFormat](../../modules/std/std-graphics-pixelformat.md),textureFlags:[TextureFlags](../../modules/mojo/mojo-graphics-textureflags.md)=TextureFlags.FilterMipmap,shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
##### Method New:Void( width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md),textureFlags:[TextureFlags](../../modules/mojo/mojo-graphics-textureflags.md)=TextureFlags.FilterMipmap,shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null )
Creates a new Image.

New( pixmap,... ) Creates an image from an existing pixmap.

New( texture,... ) Creates an image from an existing texture.

New( atlas,... ) Creates an image 'frame' from an 'atlas' image. The new images shares the same material as the atlas.

New( width,height,... ) Creates an image that can be rendered to using a canvas.

| Parameters |    |
|:-----------|:---|
| `pixmap` | pixmap Source image. |
| `texture` | texture Source texture. |
| `textureFlags` | textureFlags Image texture flags. |
| `shader` | shader Image shader. |
| `atlas` | atlas Source atlas image. |
| `rect` | rect Source rect. |
| `x,y,width,height` | x,y,width,height Source rect |
| `width,height` | width,height Image size. |
