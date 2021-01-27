_[std](../../modules/std/std-module.md):[std.graphics](../../modules/std/std-graphics.md).[Pixmap](../../modules/std/std-graphics-pixmap.md).Paste_
##### Method Paste:Void( pixmap:[Pixmap](../../modules/std/std-graphics-pixmap.md),x:[Int](../../modules/wonkey/wonkey-types-int.md),y:[Int](../../modules/wonkey/wonkey-types-int.md) )
Paste a pixmap to the pixmap.

In debug builds, a runtime error will occur if the operation would write to pixels outside of the pixmap.

Note: No alpha blending is performed - pixels in the pixmap are simply overwritten.

| Parameters |    |
|:-----------|:---|
| `pixmap` | pixmap The pixmap to paste. |
| `x` | x The x coordinate. |
| `y` | y The y coordinate. |
