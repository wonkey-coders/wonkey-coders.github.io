_[mojo](../../modules/mojo/mojo-module.md):[mojo.input](../../modules/mojo/mojo-input.md).[KeyboardDevice](../../modules/mojo/mojo-input-keyboarddevice.md).KeyReleased_
##### Method KeyReleased:[Bool](../../modules/wonkey/wonkey-types-bool.md)( key:[Key](../../modules/mojo/mojo-input-key.md) )
Checks if a key was released.

Returns true if `key` was released since the last call to KeyReleased with the same key.

If `key` is a raw key, the state of the key as it is physically positioned on US keyboards is returned.

| Parameters |    |
|:-----------|:---|
| `key` | key Key to check. |
