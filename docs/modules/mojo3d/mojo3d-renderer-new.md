_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).[Renderer](../../modules/mojo3d/mojo3d-renderer.md).New_
##### Method New:Void(  )
Creates a new renderer.

When a new renderer is created, the config setting `MOJO3D\_RENDERER` can be used to control the type of renderer created. Use "deferred" to create a deferred renderer and "foward" to create a forward renderer. See [SetConfig](--/--/modules/std/std-filesystem-SetConfig.md) for more information about config settings. By default, a deferred renderer is created for desktop and web targets and a forward renderer for mobile targets.
