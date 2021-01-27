_[mojo](../../modules/mojo/mojo-module.md):[mojo.graphics](../../modules/mojo/mojo-graphics.md).Canvas_
##### Class Canvas
The Canvas class.

Canvas objects are used to perform rendering to either a mojo [View](mojo-graphics-view.md) or an 'off screen' [Image](mojo-graphics-image.md).

To draw to a canvas, use one of the 'Draw' methods. Drawing is affected by a number of draw states, including:

* [Color](mojo-graphics-color.md) - the current drawing color. This is combined with the current alpha to produce the final rendering color and alpha values.
* [Alpha](mojo-graphics-alpha.md) - the current drawing alpha level.
* [Matrix](mojo-graphics-matrix.md) - the current drawing matrix. All drawing coordinates are multiplied by this matrix before rendering.
* [BlendMode](mojo-graphics-blendmode.md) - the blending mode for drawing, eg: opaque, alpha, additive, multiply.
* [Viewport](mojo-graphics-viewport.md) - the current viewport. All drawing coordinates are relative to the top-left of the viewport.
* [Scissor](mojo-graphics-scissor.md) - the current scissor rect. All rendering is clipped to the union of the viewport and the scissor rect.
* [Font](mojo-graphics-font.md) - The current font to use when drawing text with [DrawText](mojo-graphics-drawtext.md).

Drawing does not occur immediately. Drawing commands are 'buffered' to reduce the overhead of sending lots of draw calls to the lower level graphics API. You can force all drawing commands in the buffer to actually render using [Flush](mojo-graphics-flush.md).

| Fields | |
|:---|:---|
| [RenderAmbient](mojo-graphics-canvas-renderambient.md) |  |
| [\_iX](mojo-graphics-canvas-_ix.md) |  |
| [\_iY](mojo-graphics-canvas-_iy.md) |  |
| [\_textureFilter2](mojo-graphics-canvas-_texturefilter2.md) |  |

| Constructors | |
|:---|:---|
| [New](mojo-graphics-canvas-new.md) | Creates a canvas that renders to an image |

| Properties | |
|:---|:---|
| [Alpha](mojo-graphics-canvas-alpha.md) | The current drawing alpha level. |
| [AmbientLight](mojo-graphics-canvas-ambientlight.md) | Ambient light color for lighting mode. |
| [BlendMode](mojo-graphics-canvas-blendmode.md) | The current drawing blend mode. |
| [Color](mojo-graphics-canvas-color.md) | The current drawing color. |
| [Color2](mojo-graphics-canvas-color2.md) |  |
| [Font](mojo-graphics-canvas-font.md) | The current font for use with DrawText. |
| [GraphicsDevice](mojo-graphics-canvas-graphicsdevice.md) |  _(read only)_ |
| [IsLighting](mojo-graphics-canvas-islighting.md) | True if canvas is in lighting mode. _(read only)_ |
| [LineSmoothing](mojo-graphics-canvas-linesmoothing.md) | Smoothing enabled for DrawLine. |
| [LineWidth](mojo-graphics-canvas-linewidth.md) | The current line width for use with DrawLine. |
| [Matrix](mojo-graphics-canvas-matrix.md) | The current drawing matrix. |
| [OutlineColor](mojo-graphics-canvas-outlinecolor.md) | The current outline color. |
| [OutlineMode](mojo-graphics-canvas-outlinemode.md) | The current outline mode. |
| [OutlineWidth](mojo-graphics-canvas-outlinewidth.md) | The current outline width. |
| [PointSize](mojo-graphics-canvas-pointsize.md) | The current point size for use with DrawPoint. |
| [RenderBounds](mojo-graphics-canvas-renderbounds.md) |  _(read only)_ |
| [RenderMatrix](mojo-graphics-canvas-rendermatrix.md) |  _(read only)_ |
| [RenderTarget](mojo-graphics-canvas-rendertarget.md) | The current render target. _(read only)_ |
| [Scissor](mojo-graphics-canvas-scissor.md) | The current scissor rect. |
| [TextureFiltering](mojo-graphics-canvas-texturefiltering.md) |  |
| [TextureFilteringEnabled](mojo-graphics-canvas-texturefilteringenabled.md) | TODO! Texture filtering enabled state. |
| [Viewport](mojo-graphics-canvas-viewport.md) | The current viewport. |

| Methods | |
|:---|:---|
| [AddLight](mojo-graphics-canvas-addlight.md) | Adds a light to the canvas. |
| [AddShadowCaster](mojo-graphics-canvas-addshadowcaster.md) | Adds a shadow caster to the canvas. |
| [BeginLighting](mojo-graphics-canvas-beginlighting.md) | Puts the canvas into lighting mode. |
| [BeginRender](mojo-graphics-canvas-beginrender.md) |  |
| [Clear](mojo-graphics-canvas-clear.md) | Clears the viewport. |
| [ClearMatrix](mojo-graphics-canvas-clearmatrix.md) | Clears the internal matrix stack and sets the drawing matrix to the identitity matrix. |
| [CopyPixels](mojo-graphics-canvas-copypixels.md) | Copies a rectangular region of pixels to a pixmap. |
| [CopyPixmap](mojo-graphics-canvas-copypixmap.md) | Copies a pixmap from the rendertarget. |
| [DrawChamferRect](mojo-graphics-canvas-drawchamferrect.md) |  |
| [DrawCircle](mojo-graphics-canvas-drawcircle.md) | Draws a circle. |
| [DrawColorRect](mojo-graphics-canvas-drawcolorrect.md) |  |
| [DrawCross](mojo-graphics-canvas-drawcross.md) |  |
| [DrawDiamond](mojo-graphics-canvas-drawdiamond.md) |  |
| [DrawEllipse](mojo-graphics-canvas-drawellipse.md) | Draws an ellipse. |
| [DrawFrame](mojo-graphics-canvas-drawframe.md) | Draws a rectangle frame (made from lines). |
| [DrawFrame3d](mojo-graphics-canvas-drawframe3d.md) |  |
| [DrawFrameChamferRect](mojo-graphics-canvas-drawframechamferrect.md) |  |
| [DrawFrameCircle](mojo-graphics-canvas-drawframecircle.md) |  |
| [DrawFrameDiamond](mojo-graphics-canvas-drawframediamond.md) |  |
| [DrawFrameOval](mojo-graphics-canvas-drawframeoval.md) |  |
| [DrawFrameOvalDepth](mojo-graphics-canvas-drawframeovaldepth.md) |  |
| [DrawFrameRoundedRect](mojo-graphics-canvas-drawframeroundedrect.md) |  |
| [DrawFrameSquare](mojo-graphics-canvas-drawframesquare.md) |  |
| [DrawFrameTriangle](mojo-graphics-canvas-drawframetriangle.md) |  |
| [DrawGrid](mojo-graphics-canvas-drawgrid.md) | Draws a grid of cells (made from lines). |
| [DrawHFadeRect](mojo-graphics-canvas-drawhfaderect.md) |  |
| [DrawImage](mojo-graphics-canvas-drawimage.md) | Draws an image. |
| [DrawImageIcon](mojo-graphics-canvas-drawimageicon.md) | Draws an image icon frame. |
| [DrawImageIconRotate](mojo-graphics-canvas-drawimageiconrotate.md) |  |
| [DrawImageIconSize](mojo-graphics-canvas-drawimageiconsize.md) |  |
| [DrawImageQuad](mojo-graphics-canvas-drawimagequad.md) |  |
| [DrawImageQuadPure](mojo-graphics-canvas-drawimagequadpure.md) |  |
| [DrawImageRect](mojo-graphics-canvas-drawimagerect.md) |  |
| [DrawLine](mojo-graphics-canvas-drawline.md) | Draws a line. |
| [DrawOval](mojo-graphics-canvas-drawoval.md) | Draws an oval. |
| [DrawPoint](mojo-graphics-canvas-drawpoint.md) | Draws a point. |
| [DrawPoly](mojo-graphics-canvas-drawpoly.md) | Draws a polygon. |
| [DrawPolys](mojo-graphics-canvas-drawpolys.md) | Draws a sequence of polygons. |
| [DrawPrimitives](mojo-graphics-canvas-drawprimitives.md) | Draws a sequence of primtives. |
| [DrawQuad](mojo-graphics-canvas-drawquad.md) | Draws a quad. |
| [DrawQuadImage](mojo-graphics-canvas-drawquadimage.md) | Draws a quad from a source image. |
| [DrawQuadImageIcon](mojo-graphics-canvas-drawquadimageicon.md) | Draws a quad from a source image. |
| [DrawQuadImageSlice](mojo-graphics-canvas-drawquadimageslice.md) | Draws a quad from a source image slice. |
| [DrawQuadIntersectImage](mojo-graphics-canvas-drawquadintersectimage.md) |  |
| [DrawRect](mojo-graphics-canvas-drawrect.md) |  |
| [DrawRoundedRect](mojo-graphics-canvas-drawroundedrect.md) |  |
| [DrawSquare](mojo-graphics-canvas-drawsquare.md) |  |
| [DrawTarget](mojo-graphics-canvas-drawtarget.md) |  |
| [DrawText](mojo-graphics-canvas-drawtext.md) | Draws text. |
| [DrawTextBold](mojo-graphics-canvas-drawtextbold.md) |  |
| [DrawTextSize](mojo-graphics-canvas-drawtextsize.md) |  |
| [DrawTextSpacing](mojo-graphics-canvas-drawtextspacing.md) |  |
| [DrawTextV](mojo-graphics-canvas-drawtextv.md) |  |
| [DrawTextVSize](mojo-graphics-canvas-drawtextvsize.md) |  |
| [DrawTriangle](mojo-graphics-canvas-drawtriangle.md) |  |
| [DrawTriangleXYZ](mojo-graphics-canvas-drawtrianglexyz.md) |  |
| [DrawTriangleXYZNormal](mojo-graphics-canvas-drawtrianglexyznormal.md) |  |
| [DrawTriangleXYZNormal2](mojo-graphics-canvas-drawtrianglexyznormal2.md) |  |
| [DrawVFadeRect](mojo-graphics-canvas-drawvfaderect.md) |  |
| [DrawX](mojo-graphics-canvas-drawx.md) |  |
| [EndLighting](mojo-graphics-canvas-endlighting.md) | Renders lighting and ends lighting mode. |
| [EndRender](mojo-graphics-canvas-endrender.md) |  |
| [Flush](mojo-graphics-canvas-flush.md) | Flushes drawing commands. |
| [GetPixel](mojo-graphics-canvas-getpixel.md) | Gets a pixel color. |
| [GetPixelARGB](mojo-graphics-canvas-getpixelargb.md) | Gets a pixel color. |
| [LineIntersect](mojo-graphics-canvas-lineintersect.md) |  |
| [PopMatrix](mojo-graphics-canvas-popmatrix.md) | Pops the drawing matrix off the internal matrix stack. |
| [PushMatrix](mojo-graphics-canvas-pushmatrix.md) | Pushes the drawing matrix onto the internal matrix stack. |
| [Resize](mojo-graphics-canvas-resize.md) |  Resizes a canvas that renders to the backbuffer. |
| [Rotate](mojo-graphics-canvas-rotate.md) | Rotates the drawing matrix. |
| [Scale](mojo-graphics-canvas-scale.md) | Scales the drawing matrix. |
| [SetCol](mojo-graphics-canvas-setcol.md) |  |
| [SetCol2](mojo-graphics-canvas-setcol2.md) |  |
| [SetUserUniformCallback](mojo-graphics-canvas-setuseruniformcallback.md) |  |
| [SetViewport](mojo-graphics-canvas-setviewport.md) |  |
| [SetXYZ](mojo-graphics-canvas-setxyz.md) |  |
| [Translate](mojo-graphics-canvas-translate.md) | Translates the drawing matrix. |
