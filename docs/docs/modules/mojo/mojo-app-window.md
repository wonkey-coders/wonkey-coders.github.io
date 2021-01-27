_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).Window_
##### Class Window Extends [View](../../modules/mojo/mojo-app-view.md)
The Window class.

| Constructors | |
|:---|:---|
| [New](mojo-app-window-new.md) | Creates a new window. |

| Properties | |
|:---|:---|
| [CanRender](mojo-app-window-canrender.md) |  _(read only)_ |
| [ClearColor](mojo-app-window-clearcolor.md) | The window clear color. |
| [ClearEnabled](mojo-app-window-clearenabled.md) | True if window clearing is enabled. |
| [ContentView](mojo-app-window-contentview.md) | Window content view. |
| [DesktopHeight](mojo-app-window-desktopheight.md) |  _(read only)_ |
| [DesktopWidth](mojo-app-window-desktopwidth.md) |  _(read only)_ |
| [Fullscreen](mojo-app-window-fullscreen.md) | Window fullscreen state. |
| [IsFullscreen](mojo-app-window-isfullscreen.md) |  _(read only)_ |
| [Maximized](mojo-app-window-maximized.md) | Window maximized state. _(read only)_ |
| [Minimized](mojo-app-window-minimized.md) | Window minimized state. _(read only)_ |
| [MouseScale](mojo-app-window-mousescale.md) |  Mouse scale for ios retina devices. Should prob. be in App so @2.png can use it etc. _(read only)_ |
| [SDLGLContext](mojo-app-window-sdlglcontext.md) |  The internal SDL_GLContext used by this window. _(read only)_ |
| [SDLWindow](mojo-app-window-sdlwindow.md) |  The internal SDL_Window used by this window. _(read only)_ |
| [SwapAsync](mojo-app-window-swapasync.md) |  |
| [SwapInterval](mojo-app-window-swapinterval.md) | The window swap interval. |
| [Title](mojo-app-window-title.md) | The window title text. |
| [WindowHeight](mojo-app-window-windowheight.md) |  _(read only)_ |
| [WindowWidth](mojo-app-window-windowwidth.md) |  _(read only)_ |
| [WindowX](mojo-app-window-windowx.md) |  _(read only)_ |
| [WindowXY](mojo-app-window-windowxy.md) |  _(read only)_ |
| [WindowY](mojo-app-window-windowy.md) |  _(read only)_ |

| Methods | |
|:---|:---|
| [BeginFullscreen](mojo-app-window-beginfullscreen.md) | Switches window to fullscreen mode. |
| [ClearWindow](mojo-app-window-clearwindow.md) | Clear the window directly. |
| [EndFullscreen](mojo-app-window-endfullscreen.md) | Ends fullscreen mode. |
| [Maximize](mojo-app-window-maximize.md) | Maximizes the window. |
| [Minimize](mojo-app-window-minimize.md) | Minimizes the window. |
| [ResizeWindow](mojo-app-window-resizewindow.md) |  |
| [Restore](mojo-app-window-restore.md) | Restores the window. |
| [SendTouchEvent](mojo-app-window-sendtouchevent.md) |  |
| [SendWindowEvent](mojo-app-window-sendwindowevent.md) |  |
| [SetMinSize](mojo-app-window-setminsize.md) |  |
| [UpdateWindow](mojo-app-window-updatewindow.md) |  |
| [WindowResize](mojo-app-window-windowresize.md) | Resize the current window |

| Functions | |
|:---|:---|
| [AllWindows](mojo-app-window-allwindows.md) |  |
| [VisibleWindows](mojo-app-window-visiblewindows.md) |  |
| [WindowForID](mojo-app-window-windowforid.md) |  |

| Protected methods | |
|:---|:---|
| [OnCreateWindow](mojo-app-window-oncreatewindow.md) | Called once after a Window has been created. |
| [OnThemeChanged](mojo-app-window-onthemechanged.md) | Theme changed handler. |
| [OnTouchEvent](mojo-app-window-ontouchevent.md) | Touch event handler. |
| [OnWindowEvent](mojo-app-window-onwindowevent.md) | Window event handler. |
