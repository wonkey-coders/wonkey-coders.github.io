_[std](../../modules/std/std-module.md):[std.time](../../modules/std/std-time.md).TimeSpan_
##### Struct TimeSpan
TimeSpan class.

A time span represents the difference between 2 times. A time span can also be thought of as 'duration' or 'interval'.

Time spans are produced by subtracting times, and can be added to times to produce new times that are 'in the future' or 'in the past'.

Internally, a timespan is represented by a single signed 64 bit ticks value. A tick is 1 ten millionth of a second.

| Consts | |
|:---|:---|
| [TicksPerDay](std-time-timespan-ticksperday.md) |  |
| [TicksPerHour](std-time-timespan-ticksperhour.md) |  |
| [TicksPerMillisec](std-time-timespan-tickspermillisec.md) |  |
| [TicksPerMinute](std-time-timespan-ticksperminute.md) |  |
| [TicksPerSecond](std-time-timespan-tickspersecond.md) |  |

| Constructors | |
|:---|:---|
| [New](std-time-timespan-new.md) | Creates a new TimeSpan |

| Properties | |
|:---|:---|
| [Days](std-time-timespan-days.md) | Days in the time span. _(read only)_ |
| [Hours](std-time-timespan-hours.md) | Hours in the time span. _(read only)_ |
| [Millisecs](std-time-timespan-millisecs.md) | Millisecs in the time span. _(read only)_ |
| [Minutes](std-time-timespan-minutes.md) | Minutes in the time span. _(read only)_ |
| [Seconds](std-time-timespan-seconds.md) | Seconds in the time span. _(read only)_ |
| [Ticks](std-time-timespan-ticks.md) | Ticks in the time span. _(read only)_ |
| [TotalDays](std-time-timespan-totaldays.md) | Total days in the time span. _(read only)_ |
| [TotalHours](std-time-timespan-totalhours.md) | Total hours in the time span. _(read only)_ |
| [TotalMillisecs](std-time-timespan-totalmillisecs.md) | Total milliseconds in the time span. _(read only)_ |
| [TotalMinutes](std-time-timespan-totalminutes.md) | Total minutes in the time span. _(read only)_ |
| [TotalSeconds](std-time-timespan-totalseconds.md) | Total seconds in the time span. _(read only)_ |

| Methods | |
|:---|:---|
| [Operator To](std-time-timespan-to.md) | Converts the time span to a string. |
