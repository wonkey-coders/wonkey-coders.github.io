_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).View_
##### Class View
The View class.

| Fields | |
|:---|:---|
| [Activated](mojo-app-view-activated.md) | Invoked when a view becomes visible and active. |
| [Deactivated](mojo-app-view-deactivated.md) | Invoked when a view is no longer visible or active. |

| Constructors | |
|:---|:---|
| [New](mojo-app-view-new.md) |  |

| Properties | |
|:---|:---|
| [AcceptsKeyEvents](mojo-app-view-acceptskeyevents.md) | Whether the view accepts key events. |
| [AcceptsMouseEvents](mojo-app-view-acceptsmouseevents.md) | Whether the view accepts mouse events. |
| [Active](mojo-app-view-active.md) | View active state. _(read only)_ |
| [Bounds](mojo-app-view-bounds.md) |  _(read only)_ |
| [ClipRect](mojo-app-view-cliprect.md) | View clip rect. _(read only)_ |
| [Container](mojo-app-view-container.md) |  _(read only)_ |
| [Enabled](mojo-app-view-enabled.md) | View enabled state. |
| [Frame](mojo-app-view-frame.md) | View frame rect. |
| [Gravity](mojo-app-view-gravity.md) | Gravity for floating views. |
| [Height](mojo-app-view-height.md) | Height of the view content rect. _(read only)_ |
| [Layout](mojo-app-view-layout.md) | Layout mode. |
| [LocalMatrix](mojo-app-view-localmatrix.md) |  _(read only)_ |
| [MaxSize](mojo-app-view-maxsize.md) | Maximum view size. |
| [MinSize](mojo-app-view-minsize.md) | Minimum view size. |
| [MouseLocation](mojo-app-view-mouselocation.md) | Mouse location relative to the view. _(read only)_ |
| [Offset](mojo-app-view-offset.md) |  |
| [Parent](mojo-app-view-parent.md) | The parent view of this view. _(read only)_ |
| [Rect](mojo-app-view-rect.md) | View content rect. _(read only)_ |
| [RenderBounds](mojo-app-view-renderbounds.md) |  _(read only)_ |
| [RenderMatrix](mojo-app-view-rendermatrix.md) |  _(read only)_ |
| [RenderRect](mojo-app-view-renderrect.md) |  _(read only)_ |
| [RenderStyle](mojo-app-view-renderstyle.md) | View render style. _(read only)_ |
| [Style](mojo-app-view-style.md) | View style. |
| [StyleState](mojo-app-view-stylestate.md) | View style state. |
| [Visible](mojo-app-view-visible.md) | View visibility state. |
| [Width](mojo-app-view-width.md) | Width of the view content rect. _(read only)_ |
| [Window](mojo-app-view-window.md) | The Window this view is attached to, if any. _(read only)_ |

| Methods | |
|:---|:---|
| [AddChildView](mojo-app-view-addchildview.md) | Adds a child view to this view. |
| [FindViewAtWindowPoint](mojo-app-view-findviewatwindowpoint.md) |  |
| [GetStyle](mojo-app-view-getstyle.md) | Gets a style. |
| [InvalidateStyle](mojo-app-view-invalidatestyle.md) |  |
| [IsChildOf](mojo-app-view-ischildof.md) | Checks if the view is a child of another view. |
| [MakeKeyView](mojo-app-view-makekeyview.md) | Makes this view the key view. |
| [MeasureLayoutSize](mojo-app-view-measurelayoutsize.md) |  |
| [RemoveChildView](mojo-app-view-removechildview.md) | Removes a child view from this view. |
| [RequestRender](mojo-app-view-requestrender.md) |  |
| [SendKeyEvent](mojo-app-view-sendkeyevent.md) | Sends a key event to the view. |
| [SendMouseEvent](mojo-app-view-sendmouseevent.md) | Sends a mouse event to the view. |
| [TransformPointFromView](mojo-app-view-transformpointfromview.md) | Transforms a point from another view. |
| [TransformPointToView](mojo-app-view-transformpointtoview.md) | Transforms a point to another view. |
| [TransformRectFromView](mojo-app-view-transformrectfromview.md) | Transforms a rect from another view. |
| [TransformRectToView](mojo-app-view-transformrecttoview.md) | Transforms a rect to another view. |
| [TransformWindowPointToView](mojo-app-view-transformwindowpointtoview.md) | Transforms a point in window coordinates to view coordinates. |
| [ValidateStyle](mojo-app-view-validatestyle.md) |  |

| Protected properties | |
|:---|:---|
| [LayoutSize](mojo-app-view-layoutsize.md) | MeasuredSize plus the current [RenderStyle](mojo-app-renderstyle.md) bounds size. _(read only)_ |
| [MeasuredSize](mojo-app-view-measuredsize.md) | The last size returned by OnMeasure. _(read only)_ |
| [MouseDown](mojo-app-view-mousedown.md) | the status of the main mouse button. _(read only)_ |
| [MouseFX](mojo-app-view-mousefx.md) | Mouse X position (from 0 to 1). _(read only)_ |
| [MouseFY](mojo-app-view-mousefy.md) | Mouse Y position (from 0 to 1). _(read only)_ |
| [MouseX](mojo-app-view-mousex.md) | Mouse X position in the view. _(read only)_ |
| [MouseY](mojo-app-view-mousey.md) | Mouse Y position in the view. _(read only)_ |
| [StyleBounds](mojo-app-view-stylebounds.md) | The current [RenderStyle](mojo-app-renderstyle.md) bounds rect. _(read only)_ |

| Protected methods | |
|:---|:---|
| [Measure](mojo-app-view-measure.md) |  |
| [Measure2](mojo-app-view-measure2.md) |  |
| [OnKeyChar](mojo-app-view-onkeychar.md) | Keyboard char event handler. |
| [OnKeyDown](mojo-app-view-onkeydown.md) | Keyboard down event handler. |
| [OnKeyEvent](mojo-app-view-onkeyevent.md) | Keyboard event handler. |
| [OnKeyRepeat](mojo-app-view-onkeyrepeat.md) | Keyboard repeat event handler. |
| [OnKeyUp](mojo-app-view-onkeyup.md) | Keyboard up event handler. |
| [OnKeyViewChanged](mojo-app-view-onkeyviewchanged.md) | Called when the key view changes. |
| [OnLayout](mojo-app-view-onlayout.md) | Called during layout when the view needs to update its child views. |
| [OnMeasure](mojo-app-view-onmeasure.md) | Called during layout to measure the view. |
| [OnMeasure2](mojo-app-view-onmeasure2.md) |  |
| [OnMouseClick](mojo-app-view-onmouseclick.md) | MouseClick event handler. |
| [OnMouseDoubleClick](mojo-app-view-onmousedoubleclick.md) | MouseDoubleClick event handler. |
| [OnMouseDown](mojo-app-view-onmousedown.md) | MouseDown event handler. |
| [OnMouseEnter](mojo-app-view-onmouseenter.md) | MouseEnter event handler. |
| [OnMouseEvent](mojo-app-view-onmouseevent.md) | Mouse event handler. |
| [OnMouseLeave](mojo-app-view-onmouseleave.md) | MouseLeave event handler. |
| [OnMouseMove](mojo-app-view-onmousemove.md) | MouseMove event handler. |
| [OnMouseRightClick](mojo-app-view-onmouserightclick.md) | MouseRightClick event handler. |
| [OnMouseUp](mojo-app-view-onmouseup.md) | MouseUp event handler. |
| [OnMouseWheel](mojo-app-view-onmousewheel.md) | Mouse wheel event handler. |
| [OnRender](mojo-app-view-onrender.md) | Called when the view needs to render itself. |
| [OnThemeChanged](mojo-app-view-onthemechanged.md) | Called during layout if theme has changed. |
| [OnValidateStyle](mojo-app-view-onvalidatestyle.md) | Called during layout if [Style](mojo-app-style.md) or [StyleState](mojo-app-stylestate.md) have changed. |
| [Render](mojo-app-view-render.md) |  |
| [SetWindow](mojo-app-view-setwindow.md) |  |
| [UpdateActive](mojo-app-view-updateactive.md) |  |
| [UpdateLayout](mojo-app-view-updatelayout.md) |  |
