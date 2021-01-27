_[mojo3d](../../modules/mojo3d/mojo3d-module.md):[mojo3d](../../modules/mojo3d/mojo3d-module.md).Renderer_
##### Class Renderer
The mojo3d Renderer class.

A renderer is an object that renders scenes. There is normally only ever one renderer created and it is created for you automatically when required so you don't normally need to worry about renderers at all.

When a new renderer is created, the config setting `MOJO3D\_RENDERER` can be used to control the type of renderer created. Use "deferred" to create a deferred renderer and "foward" to create a forward renderer. See [SetConfig](--/--/modules/std/std-filesystem-SetConfig.md) for more information about config settings. By default, a deferred renderer is created for desktop and web targets and a forward renderer for mobile targets.

| Constructors | |
|:---|:---|
| [New](mojo3d-renderer-new.md) | Creates a new renderer. |

| Properties | |
|:---|:---|
| [CSMTextureSize](mojo3d-renderer-csmtexturesize.md) | Size of the cascaded shadow map texture. |
| [Deferred](mojo3d-renderer-deferred.md) | True if renderer is using deferred rendering. _(read only)_ |
| [PSMTextureSize](mojo3d-renderer-psmtexturesize.md) | Size of the cube texture used for point light shadow mapping. |
| [ShaderDefs](mojo3d-renderer-shaderdefs.md) |  _(read only)_ |

| Methods | |
|:---|:---|
| [Render](mojo3d-renderer-render.md) |  |
| [RenderBackground](mojo3d-renderer-renderbackground.md) |  |
| [RenderCopy](mojo3d-renderer-rendercopy.md) |  |
| [RenderCopyQuad](mojo3d-renderer-rendercopyquad.md) |  |
| [RenderDeferredFog](mojo3d-renderer-renderdeferredfog.md) |  |
| [RenderDeferredLighting](mojo3d-renderer-renderdeferredlighting.md) |  |
| [RenderDirectionalShadows](mojo3d-renderer-renderdirectionalshadows.md) |  |
| [RenderInvertedQuad](mojo3d-renderer-renderinvertedquad.md) |  |
| [RenderOpaque](mojo3d-renderer-renderopaque.md) |  |
| [RenderOpaqueDeferred](mojo3d-renderer-renderopaquedeferred.md) |  |
| [RenderOpaqueForward](mojo3d-renderer-renderopaqueforward.md) |  |
| [RenderOpaqueOps](mojo3d-renderer-renderopaqueops.md) |  |
| [RenderPointShadows](mojo3d-renderer-renderpointshadows.md) |  |
| [RenderPostEffects](mojo3d-renderer-renderposteffects.md) |  |
| [RenderQuad](mojo3d-renderer-renderquad.md) |  |
| [RenderRenderOps](mojo3d-renderer-renderrenderops.md) |  |
| [RenderSelfIlluminated](mojo3d-renderer-renderselfilluminated.md) |  |
| [RenderSelfIlluminatedOps](mojo3d-renderer-renderselfilluminatedops.md) |  |
| [RenderShadowOps](mojo3d-renderer-rendershadowops.md) |  |
| [RenderSpotShadows](mojo3d-renderer-renderspotshadows.md) |  |
| [RenderTransparent](mojo3d-renderer-rendertransparent.md) |  |
| [RenderTransparentOps](mojo3d-renderer-rendertransparentops.md) |  |
| [SortSpriteOps](mojo3d-renderer-sortspriteops.md) |  |
| [SortTransparentOps](mojo3d-renderer-sorttransparentops.md) |  |

| Functions | |
|:---|:---|
| [GetCurrent](mojo3d-renderer-getcurrent.md) | Gets the current renderer. |
