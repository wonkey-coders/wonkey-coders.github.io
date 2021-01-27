_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).EndLighting_
##### Method EndLighting:Void(  )
Renders lighting and ends lighting mode.

Renders any lights and shadows casters added to the canvas through calls to [AddLight](mojo-graphics-canvas-addlight.md) and [AddShadowCaster](mojo-graphics-canvas-addshadowcaster.md) and ends lighting mode.

Any lights and shadow casters added to the canvas are also removed and must be added again later if you want to render them again.

This method must be called while the canvas is in lighting mode.
