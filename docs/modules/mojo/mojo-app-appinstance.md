_[mojo](../../modules/mojo/mojo-module.md):[mojo.app](../../modules/mojo/mojo-app.md).AppInstance_
##### Class AppInstance
The AppInstance class.

The AppInstance class is mainly reponsible for running the app 'event loop', but also provides several utility functions for managing the application.

A global instance of the AppInstance class is stored in the [App](mojo-app-app.md) global variable, so you can use any member of the AppInstance simply by prefixing it with 'App.', eg: App.MilliSecs

There are a number of config settings that can be used to control app behaviour. See [SetConfig](--/--/modules/std/std-filesystem-SetConfig.md) for more information about config settings.

| Config setting		  			| Possible values					| Default value
|:----------------------------------|:----------------------------------|:-------------
| "MOJO\_OPENGL\_PROFILE"			| "es", "compatibility" or "core" 	| "compatibility" on macos and linux, "es" on all other targets. Uses 'Angle' for es support on windows.
| "MOJO\_OPENGL\_VERSION\_MAJOR"	| Open gl major version				| 2
| "MOJO\_OPENGL\_VERSION\_MINOR"	| Open gl minor version				| 0
| "MOJO\_COLOR\_BUFFER\_BITS"		| Minimum color bit depth			| 8
| "MOJO\_DEPTH\_BUFFER\_BITS"		| Minimum depth buffer bit depth	| 0
| "MOJO\_STENCIL\_BUFFER\_BITS"		| Minimum stencil buffer bit depth	| 0

| Fields | |
|:---|:---|
| [Activated](mojo-app-appinstance-activated.md) | Invoked when app is activated. |
| [Deactivated](mojo-app-appinstance-deactivated.md) | Invoked when app is deactivated. |
| [FileDropped](mojo-app-appinstance-filedropped.md) | Invoked when a file is dropped on an app window. |
| [Idle](mojo-app-appinstance-idle.md) | Invoked when the app becomes idle. |
| [KeyEventFilter](mojo-app-appinstance-keyeventfilter.md) | Key event filter. |
| [MouseEventFilter](mojo-app-appinstance-mouseeventfilter.md) | MouseEvent filter. |
| [SdlEventFilter](mojo-app-appinstance-sdleventfilter.md) | Raw SDL_Event filter. |
| [ThemeChanged](mojo-app-appinstance-themechanged.md) |  |

| Constructors | |
|:---|:---|
| [New](mojo-app-appinstance-new.md) | Creates a new app instance. |

| Properties | |
|:---|:---|
| [Active](mojo-app-appinstance-active.md) | True if app is active. _(read only)_ |
| [ActiveWindow](mojo-app-appinstance-activewindow.md) | The currently active window. _(read only)_ |
| [ClipboardText](mojo-app-appinstance-clipboardtext.md) | Clipboard text. |
| [ClipboardTextEmpty](mojo-app-appinstance-clipboardtextempty.md) | True if clipboard text is empty. _(read only)_ |
| [DefaultFont](mojo-app-appinstance-defaultfont.md) | Fallback font. _(read only)_ |
| [DefaultFontName](mojo-app-appinstance-defaultfontname.md) |  _(read only)_ |
| [DefaultMonoFont](mojo-app-appinstance-defaultmonofont.md) |  _(read only)_ |
| [DefaultMonoFontName](mojo-app-appinstance-defaultmonofontname.md) |  _(read only)_ |
| [DesktopMode](mojo-app-appinstance-desktopmode.md) | The desktop display mode. _(read only)_ |
| [DesktopSize](mojo-app-appinstance-desktopsize.md) | The desktop size. _(read only)_ |
| [FPS](mojo-app-appinstance-fps.md) | Approximate frames per second rendering rate. _(read only)_ |
| [HoverView](mojo-app-appinstance-hoverview.md) | The current hover view. _(read only)_ |
| [KeyView](mojo-app-appinstance-keyview.md) | The current key view. |
| [Millisecs](mojo-app-appinstance-millisecs.md) | Number of milliseconds app has been running. _(read only)_ |
| [ModalView](mojo-app-appinstance-modalview.md) |  _(read only)_ |
| [MouseLocation](mojo-app-appinstance-mouselocation.md) | Mouse location relative to the active window. _(read only)_ |
| [MouseView](mojo-app-appinstance-mouseview.md) | The current mouse view. _(read only)_ |
| [Renderable](mojo-app-appinstance-renderable.md) |  _(read only)_ |
| [Theme](mojo-app-appinstance-theme.md) | The current theme. _(read only)_ |

| Methods | |
|:---|:---|
| [ActiveViewAtMouseLocation](mojo-app-appinstance-activeviewatmouselocation.md) |  |
| [BeginModal](mojo-app-appinstance-beginmodal.md) | Puts app into modal mode. |
| [DispatchEvents](mojo-app-appinstance-dispatchevents.md) |  |
| [EndModal](mojo-app-appinstance-endmodal.md) | Exits app from modal mode. |
| [EnumDisplayModes](mojo-app-appinstance-enumdisplaymodes.md) | Enumerate the available display modes |
| [IsActive](mojo-app-appinstance-isactive.md) |  |
| [MainLoop](mojo-app-appinstance-mainloop.md) |  |
| [RequestRender](mojo-app-appinstance-requestrender.md) | Request that the app render itself. |
| [ResetPolledInput](mojo-app-appinstance-resetpolledinput.md) | Resets polled mouse and keyboard devices. |
| [ResumeRendering](mojo-app-appinstance-resumerendering.md) |  |
| [Run](mojo-app-appinstance-run.md) | Run the app. |
| [Sleep](mojo-app-appinstance-sleep.md) | Puts the app to sleep. |
| [SuspendRendering](mojo-app-appinstance-suspendrendering.md) |  |
| [Terminate](mojo-app-appinstance-terminate.md) | Terminate the app. |
| [UpdateWindows](mojo-app-appinstance-updatewindows.md) |  |
| [WaitIdle](mojo-app-appinstance-waitidle.md) |  |

| Functions | |
|:---|:---|
| [EmscriptenMainLoop](mojo-app-appinstance-emscriptenmainloop.md) |  |
