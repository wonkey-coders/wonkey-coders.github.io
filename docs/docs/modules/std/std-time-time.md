_[std](../../modules/std/std-module.md):[std.time](../../modules/std/std-time.md).Time_
##### Class Time
The Time class.

The Time class represents a point in time.

Note that the current implementation of the time class only has second precision.

On some 32 bit targets, it may also be suject to the year 2038 problem:

https://en.wikipedia.org/wiki/Year_2038_problem

| Consts | |
|:---|:---|
| [DayNames](std-time-time-daynames.md) |  |
| [MonthNames](std-time-time-monthnames.md) |  |

| Constructors | |
|:---|:---|
| [New](std-time-time-new.md) | Creates a new time. |

| Properties | |
|:---|:---|
| [Day](std-time-time-day.md) | Day of the month (1-31) _(read only)_ |
| [DaylightSavings](std-time-time-daylightsavings.md) | True if daylight savings is in effect. _(read only)_ |
| [Hours](std-time-time-hours.md) | Hours since midnight (0-23) _(read only)_ |
| [Minutes](std-time-time-minutes.md) | Minutes (0-59) _(read only)_ |
| [Month](std-time-time-month.md) | Month since January (0-11) _(read only)_ |
| [Seconds](std-time-time-seconds.md) | Seconds (0-61) _(read only)_ |
| [WeekDay](std-time-time-weekday.md) | Week day since Sunday (0-6) _(read only)_ |
| [Year](std-time-time-year.md) | Year _(read only)_ |
| [YearDay](std-time-time-yearday.md) | Days since January 1 (0-365) _(read only)_ |

| Methods | |
|:---|:---|
| [Operator +](std-time-time-opadd.md) | Overloaded addition operator. |
| [Operator -](std-time-time-opsub.md) | Overloaded subtraction operator. |
| [Operator <=>](std-time-time-opcmp.md) | Overloaded comparison operator. |
| [ToString](std-time-time-tostring.md) | Converts time to a string. |
| [Operator To](std-time-time-to.md) | Converts time to a string. |

| Functions | |
|:---|:---|
| [FromFileTime](std-time-time-fromfiletime.md) | Converts a file time to a time. |
| [Now](std-time-time-now.md) | Gets current time. |
| [Parse](std-time-time-parse.md) | Parses a time from a string. |
