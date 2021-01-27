_[mojo](../../modules/mojo/mojo-module.md):[mojo.input](../../modules/mojo/mojo-input.md).[KeyboardDevice](../../modules/mojo/mojo-input-keyboarddevice.md).KeyPressed_
##### Method KeyPressed:[Bool](../../modules/wonkey/wonkey-types-bool.md)( key:[Key](../../modules/mojo/mojo-input-key.md),repeating:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Checks if a key was pressed.

Returns true if `key` was pressed since the last call to KeyPressed with the same key.

If `key` is a raw key, the state of the key as it is physically positioned on US keyboards is returned.

if `repeating` is true, then key repeats are included.

| Parameters |    |
|:-----------|:---|
| `key` | key Key to check. |
