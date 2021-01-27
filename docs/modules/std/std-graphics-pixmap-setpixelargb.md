_[std](../../modules/std/std-module.md):[std.graphics](../../modules/std/std-graphics.md).[Pixmap](../../modules/std/std-graphics-pixmap.md).SetPixelARGB_
##### Method SetPixelARGB:Void( x:[Int](../../modules/wonkey/wonkey-types-int.md),y:[Int](../../modules/wonkey/wonkey-types-int.md),color:[UInt](../../modules/wonkey/wonkey-types-uint.md) )
Sets a pixel to an ARGB color.

Sets the pixel at `x`, `y` to `pixel`.

In debug builds, a runtime error will occur if the pixel coordinates lie outside of the pixmap area.

| Parameters |    |
|:-----------|:---|
| `x` | x The x coordinate of the pixel. |
| `y` | y The y coordinate of the pixel. |
| `color` | color The pixel to set in ARGB format. |
