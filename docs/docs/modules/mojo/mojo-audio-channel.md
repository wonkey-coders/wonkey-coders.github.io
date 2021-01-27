_[mojo](../../modules/mojo/mojo-module.md):[mojo.audio](../../modules/mojo/mojo-audio.md).Channel_
##### Class Channel Extends [std.resource.Resource](../../modules/std/std-resource-resource.md)

| Constructors | |
|:---|:---|
| [New](mojo-audio-channel-new.md) | Creates a new audio channel. |

| Properties | |
|:---|:---|
| [Flags](mojo-audio-channel-flags.md) |  _(read only)_ |
| [Pan](mojo-audio-channel-pan.md) | Channel pan in the range -1 (left) to 1 (right). |
| [Paused](mojo-audio-channel-paused.md) | True if channel is paused. |
| [Pitch](mojo-audio-channel-pitch.md) | Channel playback rate. |
| [Playhead](mojo-audio-channel-playhead.md) | Channel playhead in samples. |
| [PlayheadSample](mojo-audio-channel-playheadsample.md) | Channel playhead sample offset. |
| [PlayheadTime](mojo-audio-channel-playheadtime.md) | Channel playhead time offset. |
| [Playing](mojo-audio-channel-playing.md) | True if channel is playing audio. _(read only)_ |
| [Rate](mojo-audio-channel-rate.md) | Channel playback rate. |
| [Stereo](mojo-audio-channel-stereo.md) | True if channel is playing a stereo audio file. |
| [Volume](mojo-audio-channel-volume.md) | Channel volume in the range 0 to 1. |

| Methods | |
|:---|:---|
| [Play](mojo-audio-channel-play.md) | Plays a sound through the channel. |
| [Queue](mojo-audio-channel-queue.md) |  - Highly experimental!!!!! |
| [Stop](mojo-audio-channel-stop.md) | Stops channel. |
| [WaitQueued](mojo-audio-channel-waitqueued.md) |  - Highly experimental!!!!! |

| Protected methods | |
|:---|:---|
| [OnDiscard](mojo-audio-channel-ondiscard.md) |  |
| [OnFinalize](mojo-audio-channel-onfinalize.md) |  |
