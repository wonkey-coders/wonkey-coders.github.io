_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawImageIcon_
##### Method DrawImageIcon:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),iconNumber:[Int](../../modules/wonkey/wonkey-types-int.md),iconCount:[Int](../../modules/wonkey/wonkey-types-int.md),rotate:[Float](../../modules/wonkey/wonkey-types-float.md)=0 )
##### Method DrawImageIcon:Void( image:[Image](../../modules/mojo/mojo-graphics-image.md),tx:[Float](../../modules/wonkey/wonkey-types-float.md),ty:[Float](../../modules/wonkey/wonkey-types-float.md),iconNumber:[Int](../../modules/wonkey/wonkey-types-int.md),iconCount:[Int](../../modules/wonkey/wonkey-types-int.md),sx:[Float](../../modules/wonkey/wonkey-types-float.md),sy:[Float](../../modules/wonkey/wonkey-types-float.md) )
Draws an image icon frame.
Draws an image using the current [Color](mojo-graphics-canvas-color.md), [BlendMode](mojo-graphics-canvas-blendmode.md) and [Matrix](mojo-graphics-canvas-matrix.md).

| Parameters |    |
|:-----------|:---|
| `tx` | tx X coordinate to draw image at. |
| `ty` | ty Y coordinate to draw image at. |
| `tx1` | tx1 X1 coordinate to draw image to. |
| `ty1` | ty1 Y1 coordinate to draw image to. |
| `iconNumber` | iconNumber number from 0 of the icon frame to draw (frames start from 0 and go left to right in equal pixel amounts). |
| `iconCount` | iconCount how many icon frames are packed into the image |
| `sx` | sx X axis scale factor for drawing. |
| `sy` | sy Y axis scale factor for drawing. |
| `rotate` | rotate (in radians) of the icon. 0 = no rotation |
