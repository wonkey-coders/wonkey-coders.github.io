_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).[Canvas](../../modules/mojo/mojo-graphics-canvas.md).BeginLighting_
##### Method BeginLighting:Void(  )
Puts the canvas into lighting mode.

While in lighting mode, you can add lights and shadow casters to the cavas using [AddLight](mojo-graphics-canvas-addlight.md) and [AddShadowCaster](mojo-graphics-canvas-addshadowcaster.md). Lights and shadows
are later rendered by calling [EndLighting](mojo-graphics-canvas-endlighting.md).

Each call to BeginLighting must be matched with a corresponding call to EndLighting.

The following properties must not be modified while in lighting mode: [Viewport](mojo-graphics-canvas-viewport.md), [Scissor](mojo-graphics-canvas-scissor.md), [AmbientLight](mojo-graphics-canvas-ambientlight.md). Attempting to
modify these properties while in lighting mode will result in a runtime error in debug builds.

The following methods must not be called in lighting mode: [Clear](mojo-graphics-canvas-clear.md), [BeginLighting](mojo-graphics-canvas-beginlighting.md). Attepting to call these methods while in
lighting mode will result in a runtime error in debug builds.
