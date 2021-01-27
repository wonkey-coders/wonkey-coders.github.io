_[mojo](../../modules/mojo/mojo-module.md):[mojo.audio](../../modules/mojo/mojo-audio.md).[Channel](../../modules/mojo/mojo-audio-channel.md).PlayheadSample_
##### Property PlayheadSample:[Int](../../modules/wonkey/wonkey-types-int.md)
Channel playhead sample offset.

Gets or sets the sample offset of the sound currently playing.

If the channel is playing when set, playback is immediately affected.

If the channel is not playing when set, the offset will be applied when the Play method is invoked.
