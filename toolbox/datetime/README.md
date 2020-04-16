# Introduction
The **DateTime Nodes** are used when working with the representation and calculation of anything relating to dates and/or times.

The way in way that the **Nodes** function may seem quite technical, with certain conventions, standards and terminology, therefore we have provided a basic overview of some of the [terminology](#terminology) to take into consideration and some links to [further information](#contents).

# Terminology
## UTC

[Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) (UTC), is a standard time basis around the world. The universal time standard was formerly Greenwich Meantime (GMT), but in order to create a differentiation between a time-*zone* and a time *standard*, UTC was adopted.

## Timezones

With UTC as a basis, all timezones in the world can be defined by their relation to the standard. GMT is denoted as UTC because there is no offset, whereas Central European Time (CET) is denoted as UTC+01, because it is an hour ahead of UTC.

## DST

It is common around the world for countries to switch to an alternative timezone at certain times of the year to better align time of daylight with things like road-usage and business hours.

Germany and other parts of Europe, for example, use Central European Summer Time (CEST or UTC+02) between March and October, but use Central European Time (CET or UTC+01) the rest of the year.

## Unix Time

The Unix Time Stamp is a way of representing, and keeping track of time on computers and other electronic devices. It represents the number of milliseconds since the Unix Epoch (1st January 1970). The reason this is used is because its data size is very small (an unsigned 32-Bit integer) and can be used as a basis for representing a date and/or time in a more human-readable way.

# Contents

- [**Date Time Formatter**](date-time-formatter.md)
- [**Now (UTC)**](now-utc.md)
- [**System Time**](system-time.md)
- [**Timezone Value**](timezone-value.md)

# External Links

- [*UTC - The World's Time Standard*](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
- [*UTC Time Offsets*](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
- [*Epoch Unix Time Stamp Converter*](https://www.unixtimestamp.com/) on unixtimestamp.com.
- [*Current Millis*](https://currentmillis.com/) on currentmillis.com.
- [*Time Zone Map*](https://www.timeanddate.com/time/map/) on timeanddate.com.