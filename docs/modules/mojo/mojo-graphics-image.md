_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).Image_
##### Class Image Extends [std.resource.Resource](../../modules/std/std-resource-resource.md)
The Image class.

An image is a rectangular array of pixels that can be drawn to a canvas using one of the [Canvas.DrawImage](mojo-graphics-canvas.drawimage.md) methods.

Images are similar to pixmap's, except that they are optimized for rendering, and typically live in GPU memory.

To load an image from a file, use one of the [Load](mojo-graphics-load.md), [LoadBump](mojo-graphics-loadbump.md) or [LoadLight](mojo-graphics-loadlight.md) functions.

To create an image from an existing pixmap, use the New( pixmap,... ) constructor.

To create an image that is a 'window' into an existing image, use the New( atlas,rect... ) constructor. This allows you to use images as 'atlases',

To create an 'empty' image, use the New( width,height ) constructor. You can then render to this image by creating a canvas with this image as its render target.

Images also have several properties that affect how they are rendered, including:

* Handle - the relative position of the image's centre (or 'pivot point') for rendering, where (0.0,0.0) means the top-left of the image while (1.0,1.0) means the bottom-right.
* Scale - a fixed scale factor for the image.
* BlendMode - controls how the image is blended with the contents of the canvas. If this is null, this property is ignored and the current canvas blendmode is used to render the image instead.
* Color - when rendering an image to a canvas, this property is multiplied by the current canvas color and the result is multiplied by actual image pixel colors to achieve the final color to be rendered.

| Constructors | |
|:---|:---|
| [New](mojo-graphics-image-new.md) | Creates a new Image. |

| Properties | |
|:---|:---|
| [BlendMode](mojo-graphics-image-blendmode.md) | The image blend mode. |
| [Bounds](mojo-graphics-image-bounds.md) | The image bounds. _(read only)_ |
| [Color](mojo-graphics-image-color.md) | The image color. |
| [FilePath](mojo-graphics-image-filepath.md) | Image filepath. |
| [Handle](mojo-graphics-image-handle.md) | The image handle. |
| [Height](mojo-graphics-image-height.md) | Image bounds height. _(read only)_ |
| [LightDepth](mojo-graphics-image-lightdepth.md) | The image light depth. |
| [Material](mojo-graphics-image-material.md) | Image material. _(read only)_ |
| [Radius](mojo-graphics-image-radius.md) | Image bounds radius. _(read only)_ |
| [Rect](mojo-graphics-image-rect.md) | The image's texture rect. _(read only)_ |
| [Scale](mojo-graphics-image-scale.md) | The image scale. |
| [Shader](mojo-graphics-image-shader.md) | Image shader. |
| [ShadowCaster](mojo-graphics-image-shadowcaster.md) | Shadow caster attached to image. |
| [TexCoords](mojo-graphics-image-texcoords.md) |  Image texture coorinates. _(read only)_ |
| [Texture](mojo-graphics-image-texture.md) | The image's primary texture. |
| [Vertices](mojo-graphics-image-vertices.md) |  Image vertices. _(read only)_ |
| [Width](mojo-graphics-image-width.md) | Image bounds width. _(read only)_ |

| Methods | |
|:---|:---|
| [GetPixel](mojo-graphics-image-getpixel.md) | Gets a pixel color. |
| [GetPixelARGB](mojo-graphics-image-getpixelargb.md) | Gets a pixel color. |
| [GetTexture](mojo-graphics-image-gettexture.md) |  gets an image's texture. |
| [SetTexture](mojo-graphics-image-settexture.md) |  Sets an image texture. |

| Functions | |
|:---|:---|
| [Load](mojo-graphics-image-load.md) | Loads an image from file. |
| [LoadBump](mojo-graphics-image-loadbump.md) | Loads a bump image from file(s). |
| [LoadLight](mojo-graphics-image-loadlight.md) | Loads a light image from file. |

| Protected methods | |
|:---|:---|
| [OnDiscard](mojo-graphics-image-ondiscard.md) |  |
