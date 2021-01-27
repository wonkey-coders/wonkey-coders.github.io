_[std](../../modules/std/std-module.md):[std.graphics](../../modules/std/std-graphics.md).[Pixmap](../../modules/std/std-graphics-pixmap.md).New_
##### Method New:Void( width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md),format:[PixelFormat](../../modules/std/std-graphics-pixelformat.md)=PixelFormat.RGBA8 )
##### Method New:Void( width:[Int](../../modules/wonkey/wonkey-types-int.md),height:[Int](../../modules/wonkey/wonkey-types-int.md),format:[PixelFormat](../../modules/std/std-graphics-pixelformat.md),data:[UByte](../../modules/wonkey/wonkey-types-ubyte.md) Ptr,pitch:[Int](../../modules/wonkey/wonkey-types-int.md) )
Creates a new pixmap.

When you have finished with the pixmap, you should call its inherited [resource.Resource.Discard](std-graphics-pixmap-resource.resource.discard.md) method.

| Parameters |    |
|:-----------|:---|
| `width` | width The width of the pixmap in pixels. |
| `height` | height The height of the pixmap in pixels. |
| `format` | format The pixmap format. |
| `data` | data A pointer to the pixmap data. |
| `pitch` | pitch The pitch of the data. |
