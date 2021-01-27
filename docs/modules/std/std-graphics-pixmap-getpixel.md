_[std](../../modules/std/std-module.md):[std.graphics](../../modules/std/std-graphics.md).[Pixmap](../../modules/std/std-graphics-pixmap.md).GetPixel_
##### Method GetPixel:[Color](../../modules/std/std-graphics-color.md)( x:[Int](../../modules/wonkey/wonkey-types-int.md),y:[Int](../../modules/wonkey/wonkey-types-int.md) )
Gets the color of a pixel.

Gets the pixel at `x`, `y` and returns it in ARGB format.

In debug builds, a runtime error will occur if the pixel coordinates lie outside of the pixmap area.

| Parameters |    |
|:-----------|:---|
| `x` | x The x coordinate of the pixel. |
| `y` | y The y coordinate of the pixel. |
