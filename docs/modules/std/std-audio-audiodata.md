_[std](../../modules/std/std-module.md):[std.audio](../../modules/std/std-audio.md).AudioData_
##### Class AudioData Extends [Resource](../../modules/std/std-resource-resource.md)
The AudioData class.

| Constructors | |
|:---|:---|
| [New](std-audio-audiodata-new.md) | Creates a new AudioData object |

| Properties | |
|:---|:---|
| [BitCount](std-audio-audiodata-bitcount.md) | The original bitcount 8/12/16/24/32 |
| [Bits](std-audio-audiodata-bits.md) | The bitsize, this will be either 8 or 16. _(read only)_ |
| [Data](std-audio-audiodata-data.md) | The actual audio data. _(read only)_ |
| [Duration](std-audio-audiodata-duration.md) | The duration, in seconds, of the audio. _(read only)_ |
| [Echo](std-audio-audiodata-echo.md) |  |
| [Filter](std-audio-audiodata-filter.md) |  |
| [Format](std-audio-audiodata-format.md) | The format of the audio. _(read only)_ |
| [Hertz](std-audio-audiodata-hertz.md) | The playback rate of the audio. _(read only)_ |
| [Length](std-audio-audiodata-length.md) | The length, in samples, of the audio. _(read only)_ |
| [Locked](std-audio-audiodata-locked.md) |  _(read only)_ |
| [Loop](std-audio-audiodata-loop.md) | Returns true if a loop has been set |
| [LoopEnd](std-audio-audiodata-loopend.md) |  |
| [LoopStart](std-audio-audiodata-loopstart.md) |  |
| [Mode1](std-audio-audiodata-mode1.md) | Returns true if a CMI Mode1 voice  has been detected |
| [Path](std-audio-audiodata-path.md) |  |
| [Porta](std-audio-audiodata-porta.md) |  |
| [PortaSpeed](std-audio-audiodata-portaspeed.md) |  |
| [Size](std-audio-audiodata-size.md) | The size, in bytes of the audio data. _(read only)_ |
| [StartSeg](std-audio-audiodata-startseg.md) |  |
| [Stereo](std-audio-audiodata-stereo.md) | Is the Audio Stereo? This will be either true for stereo or false for mono. _(read only)_ |
| [Volume](std-audio-audiodata-volume.md) |  |
| [Volume2](std-audio-audiodata-volume2.md) |  |

| Methods | |
|:---|:---|
| [Clear](std-audio-audiodata-clear.md) |  |
| [Copy](std-audio-audiodata-copy.md) |  |
| [GetSample](std-audio-audiodata-getsample.md) | Gets a sample at a given sample index. |
| [GetSampleMono16](std-audio-audiodata-getsamplemono16.md) |  |
| [GetSampleMono8](std-audio-audiodata-getsamplemono8.md) |  |
| [GetSampleStereo16](std-audio-audiodata-getsamplestereo16.md) |  |
| [GetSampleStereo8](std-audio-audiodata-getsamplestereo8.md) |  |
| [SetSample](std-audio-audiodata-setsample.md) | Sets a sample at a given sample index. |
| [SetSampleMono16](std-audio-audiodata-setsamplemono16.md) |  |
| [SetSampleMono8](std-audio-audiodata-setsamplemono8.md) |  |
| [SetSampleStereo16](std-audio-audiodata-setsamplestereo16.md) |  |
| [SetSampleStereo8](std-audio-audiodata-setsamplestereo8.md) |  |

| Functions | |
|:---|:---|
| [Load](std-audio-audiodata-load.md) | Loads audio data from a file. |

| Protected methods | |
|:---|:---|
| [OnDiscard](std-audio-audiodata-ondiscard.md) |  |
| [OnFinalize](std-audio-audiodata-onfinalize.md) |  |
