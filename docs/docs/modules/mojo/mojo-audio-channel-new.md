_[mojo](../../modules/mojo/mojo-module.md):[mojo.audio](../../modules/mojo/mojo-audio.md).[Channel](../../modules/mojo/mojo-audio-channel.md).New_
##### Method New:Void( flags:[ChannelFlags](../../modules/mojo/mojo-audio-channelflags.md)=Null )
Creates a new audio channel.

If `flags` is ChannelFlags.AutoDiscard, then the channel will be automatically discarded when it finishes playing, or when it is
stopped using [Stop](mojo-audio-channel-stop.md).
