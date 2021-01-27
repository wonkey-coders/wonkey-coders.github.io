_[mojo](../../modules/mojo/mojo-module.md):[mojo.input](../../modules/mojo/mojo-input.md).[KeyboardDevice](../../modules/mojo/mojo-input-keyboarddevice.md).KeyName_
##### Method KeyName:[String](../../modules/wonkey/wonkey-types-string.md)( key:[Key](../../modules/mojo/mojo-input-key.md) )
Gets the name of a key.

If `key` is a raw key, returns the name 'printed' on the key, eg: KeyName( Key.W|Key.Raw ) will always return the name of key at the top left of the QWERTY keys.

if `key` is a virtual key, returns the name of the key, eg: KeyName( Key.W ) will always return "W".
