_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).DrawQuadImageSlice_
##### Method DrawQuadImageSlice:Void( x0:[Float](../../modules/wonkey/wonkey-types-float.md),y0:[Float](../../modules/wonkey/wonkey-types-float.md),x1:[Float](../../modules/wonkey/wonkey-types-float.md),y1:[Float](../../modules/wonkey/wonkey-types-float.md),x2:[Float](../../modules/wonkey/wonkey-types-float.md),y2:[Float](../../modules/wonkey/wonkey-types-float.md),x3:[Float](../../modules/wonkey/wonkey-types-float.md),y3:[Float](../../modules/wonkey/wonkey-types-float.md),srcVoxImage:[ImageSlice](../../modules/mojo/mojo-graphics-imageslice.md),sliceNumber:[Int](../../modules/wonkey/wonkey-types-int.md),FrameNumber:[Int](../../modules/wonkey/wonkey-types-int.md) )
Draws a quad from a source image slice.

The source image is used and drawn at the given quad position in the current [Color](mojo-graphics-canvas-color.md) using the current [BlendMode](mojo-graphics-canvas-blendmode.md).

The quad vertex coordinates are also transformed by the current [Matrix](mojo-graphics-canvas-matrix.md).
