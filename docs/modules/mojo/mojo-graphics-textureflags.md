_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).TextureFlags_
##### Enum TextureFlags
Texture flags.

| TextureFlags	| Description
|:--------------|:-----------
| WrapS			| Wrap S texture coordinates
| WrapT			| Wrap T texture coordinates
| WrapST		| Wrap both S and T coordinates
| Filter		| Enable magnification filtering
| Mipmap		| Enable minification mipmapping, and minification filtering if Filter enabled.
| FilterMipmap	| Enable both filterin and mipmapping.
| Dynamic		| The texture contents are regularly updated and don't need to be preserved.
| Cubemap		| The texture is a cubmap.
