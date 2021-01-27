_[mojo](../../modules/mojo/mojo-module.md):[mojo.input](../../modules/mojo/mojo-input.md).KeyboardDevice_
##### Class KeyboardDevice
The KeyboardDevice class.

To access the keyboard device, use the global [Keyboard](mojo-input-keyboard.md) constant.

The keyboard device should only used after a new [AppInstance](mojo-input-appinstance.md) is created.

All methods that take a `key` parameter can also be combined with 'raw' keys.

A raw key represents the physical location of a key on US keyboards. For example, `Key.Q|Key.Raw` indicates the key at the top left of the
QWERTY keys, as this is where the 'Q' key is on US keyboards.

| Properties | |
|:---|:---|
| [Modifiers](mojo-input-keyboarddevice-modifiers.md) | The current state of the modifier keys. _(read only)_ |

| Methods | |
|:---|:---|
| [FlushChars](mojo-input-keyboarddevice-flushchars.md) | Flushes the character queue. |
| [FlushKeys](mojo-input-keyboarddevice-flushkeys.md) | Flushes all keyboard input. |
| [GetChar](mojo-input-keyboarddevice-getchar.md) | Gets the next character from the character queue. |
| [Init](mojo-input-keyboarddevice-init.md) |  |
| [KeyCodeToKey](mojo-input-keyboarddevice-keycodetokey.md) |  |
| [KeyDown](mojo-input-keyboarddevice-keydown.md) | Checks the current up/down state of a key. |
| [KeyFromName](mojo-input-keyboarddevice-keyfromname.md) | Gets the key by a given name. |
| [KeyHit](mojo-input-keyboarddevice-keyhit.md) |  |
| [KeyName](mojo-input-keyboarddevice-keyname.md) | Gets the name of a key. |
| [KeyPressed](mojo-input-keyboarddevice-keypressed.md) | Checks if a key was pressed. |
| [KeyReleased](mojo-input-keyboarddevice-keyreleased.md) | Checks if a key was released. |
| [PeekChar](mojo-input-keyboarddevice-peekchar.md) | Peeks at the next character in the character queue. |
| [Reset](mojo-input-keyboarddevice-reset.md) |  |
| [ScanCode](mojo-input-keyboarddevice-scancode.md) |  |
| [ScanCodeToRawKey](mojo-input-keyboarddevice-scancodetorawkey.md) |  |
| [SendEvent](mojo-input-keyboarddevice-sendevent.md) |  |
| [TranslateKey](mojo-input-keyboarddevice-translatekey.md) | Translates a key to/from a raw key. |
| [Update](mojo-input-keyboarddevice-update.md) |  |
