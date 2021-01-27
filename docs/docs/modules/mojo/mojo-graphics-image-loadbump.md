_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Image](../../modules/mojo/mojo-graphics-image.md).LoadBump_
##### Function LoadBump:[Image](../../modules/mojo/mojo-graphics-image.md)( diffuse:[String](../../modules/wonkey/wonkey-types-string.md),normal:[String](../../modules/wonkey/wonkey-types-string.md),specular:[String](../../modules/wonkey/wonkey-types-string.md),specularScale:[Float](../../modules/wonkey/wonkey-types-float.md)=1,flipNormalY:[Bool](../../modules/wonkey/wonkey-types-bool.md)=true,shader:[Shader](../../modules/mojo/mojo-graphics-shader.md)=Null,textureFlags:[TextureFlags](../../modules/mojo/mojo-graphics-textureflags.md)=TextureFlags.FilterMipmap )
Loads a bump image from file(s).

`diffuse`, `normal` and `specular` are filepaths of the diffuse, normal and specular image files respectively.

`specular` can be null, in which case `specularScale` is used for the specular component. Otherwise, `specularScale` is used to modulate the red component of the specular texture.
