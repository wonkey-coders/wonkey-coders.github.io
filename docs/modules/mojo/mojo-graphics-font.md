_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).Font_
##### Class Font Extends [std.resource.Resource](../../modules/std/std-resource-resource.md)
The Font class.

Fonts are used when drawing text to a canvas using [Canvas.DrawText](mojo-graphics-canvas.drawtext.md).

To load a font, use the [Font.Load](mojo-graphics-font.load.md) function. Fonts should be in .otf, .ttf or .fon format.

Once a font is loaded it can be used with a canvas via the [Canvas.Font](mojo-graphics-canvas.font.md) property.

| Properties | |
|:---|:---|
| [FirstChar](mojo-graphics-font-firstchar.md) | The first character in the font. _(read only)_ |
| [Height](mojo-graphics-font-height.md) | The font height in pixels. _(read only)_ |
| [NumChars](mojo-graphics-font-numchars.md) | The number of characters in the font. _(read only)_ |

| Methods | |
|:---|:---|
| [GetGlyph](mojo-graphics-font-getglyph.md) | Gets the glyph for a character. |
| [GetGlyphPage](mojo-graphics-font-getglyphpage.md) | Gets the glyph page for a character. |
| [GetKerning](mojo-graphics-font-getkerning.md) | Gets the kerning between 2 characters. |
| [TextWidth](mojo-graphics-font-textwidth.md) | Measures the width of some text when rendered by the font. |

| Functions | |
|:---|:---|
| [Load](mojo-graphics-font-load.md) | Loads a font from a file. |
