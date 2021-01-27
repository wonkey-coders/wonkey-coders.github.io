_[std](../../modules/std/std-module.md):[std.graphics](../../modules/std/std-graphics.md).Pixmap_
##### Class Pixmap Extends [Resource](../../modules/std/std-resource-resource.md)
Pixmaps allow you to store and manipulate rectangular blocks of pixel data.

A pixmap contains a block of memory used to store a rectangular array of pixels.

| Constructors | |
|:---|:---|
| [New](std-graphics-pixmap-new.md) | Creates a new pixmap. |

| Properties | |
|:---|:---|
| [Data](std-graphics-pixmap-data.md) | The raw pixmap data. _(read only)_ |
| [Depth](std-graphics-pixmap-depth.md) | The pixmap depth. _(read only)_ |
| [FilePath](std-graphics-pixmap-filepath.md) | Image filepath. |
| [Format](std-graphics-pixmap-format.md) | The pixmap format. _(read only)_ |
| [HasAlpha](std-graphics-pixmap-hasalpha.md) | True if pixmap format includes alpha. _(read only)_ |
| [Height](std-graphics-pixmap-height.md) | The pixmap height. _(read only)_ |
| [Pitch](std-graphics-pixmap-pitch.md) | The pixmap pitch. _(read only)_ |
| [Size](std-graphics-pixmap-size.md) | The width and height of the pixmap. _(read only)_ |
| [Width](std-graphics-pixmap-width.md) | The pixmap width. _(read only)_ |

| Methods | |
|:---|:---|
| [Clear](std-graphics-pixmap-clear.md) | Clears the pixmap to a given color. |
| [ClearARGB](std-graphics-pixmap-clearargb.md) | Clears the pixmap to an ARGB color. |
| [Convert](std-graphics-pixmap-convert.md) | Converts the pixmap to a different format. |
| [Copy](std-graphics-pixmap-copy.md) | Creates a copy of the pixmap. |
| [FlipY](std-graphics-pixmap-flipy.md) | Flips the pixmap on the Y axis. |
| [GetPixel](std-graphics-pixmap-getpixel.md) | Gets the color of a pixel. |
| [GetPixelARGB](std-graphics-pixmap-getpixelargb.md) | Gets the ARGB color of a pixel. |
| [MipHalve](std-graphics-pixmap-miphalve.md) |  Halves the pixmap for mipmapping |
| [Paste](std-graphics-pixmap-paste.md) | Paste a pixmap to the pixmap. |
| [PixelPtr](std-graphics-pixmap-pixelptr.md) | Gets a pointer to a pixel in the pixmap. |
| [PremultiplyAlpha](std-graphics-pixmap-premultiplyalpha.md) | Premultiply pixmap r,g,b components by alpha. |
| [Save](std-graphics-pixmap-save.md) | Saves the pixmap to a file. |
| [SetPixel](std-graphics-pixmap-setpixel.md) | Sets a pixel to a color. |
| [SetPixelARGB](std-graphics-pixmap-setpixelargb.md) | Sets a pixel to an ARGB color. |
| [Window](std-graphics-pixmap-window.md) | Returns a rectangular window into the pixmap. |

| Functions | |
|:---|:---|
| [Load](std-graphics-pixmap-load.md) | Loads a pixmap from a file. |

| Protected methods | |
|:---|:---|
| [OnDiscard](std-graphics-pixmap-ondiscard.md) |  |
| [OnFinalize](std-graphics-pixmap-onfinalize.md) |  |
