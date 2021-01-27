_[mojo](../../modules/mojo/mojo-module.md):[mojo.audio](../../modules/mojo/mojo-audio.md).[AudioDevice](../../modules/mojo/mojo-audio-audiodevice.md).PlayMusic_
##### Method PlayMusic:[Channel](../../modules/mojo/mojo-audio-channel.md)( path:[String](../../modules/wonkey/wonkey-types-string.md),finished:Void()=Null,paused:[Bool](../../modules/wonkey/wonkey-types-bool.md)=false )
Starts streaming audio playback.

PlayMusic starts a piece of audio streaming from a file in the background.

When the audio finishes, the optional `finished` function is invoked.

The returned [Channel](mojo-audio-audiodevice-channel.md) instance is automatically discarded when the audio stops, so should not be discarded by your code.

The audio file must be in .ogg format.
