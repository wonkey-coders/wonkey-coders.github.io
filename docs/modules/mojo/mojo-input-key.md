_[mojo](../../modules/mojo/mojo-module.md):[mojo.input](../../modules/mojo/mojo-input.md).Key_
##### Enum Key
Key codes.

By default, key codes refer to 'virtual' keys. For example, `Key.W` refers to the key with 'W' printed on it. However, this key may not be
in the same physical location on all users' keyboards, due to OS language and keyboard settings.

To deal with this, mojo also provides support for 'raw' keys. A raw key code is simply a virtual key code 'or'ed with the special key code
`Key.Raw`.
A raw key represents the physical location of a key on US keyboards. For example, `Key.Q|Key.Raw` indicates the key at the top left of the

`Key.Raw` is to be used with the [KeyboardDevice](mojo-input-keyboarddevice.md) Class only. For example `Keyboard.KeyPressed(Key.A|Key.Raw)`.

| Key
|:---
| A
| B
| C
| D
| E
| F
| G
| H
| I
| J
| K
| L
| M
| N
| O
| P
| Q
| R
| S
| T
| U
| V
| W
| X
| Y
| Z
| Key0
| Key1
| Key2
| Key3
| Key4
| Key5
| Key6
| Key7
| Key8
| Key9
| Enter
| Escape
| Backspace
| Tab
| Space
| Minus
| Equals
| LeftBracket
| RightBracket
| Backslash
| Semicolon
| Apostrophe
| Grave
| Comma
| Period
| Slash
| CapsLock
| F1
| F2
| F3
| F4
| F5
| F6
| F7
| F8
| F9
| F10
| F11
| F12
| PrintScreen
| ScrollLock
| Pause
| Insert
| Home
| PageUp
| KeyDelete
| KeyEnd
| PageDown
| Right
| Left
| Down
| Up
| LeftControl
| LeftShift
| LeftAlt
| LeftGui
| RightControl
| RightShift
| RightAlt
| RightGui
| Mode
| AudioNext
| AudioPrev
| AudioStop
| AudioPlay
| AudioMute
| MediaSelect
| WWW
| Mail
| Calculator
| Computer
| ACSearch
| ACHome
| ACBack
| ACForward
| ACStop
| ACRefresh
| ACBookmarks
| BrightnessDown
| BrightnessUp
| DisplaySwitch
| IllumToggle
| IllumDown
| IllumUp
| Eject
| Sleep
