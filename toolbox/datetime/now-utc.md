# Overview

![](../../../.gitbook/assets/node-now-utc.png)

**Now (UTC)** is used for getting the current [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) (UTC), which is a standard time basis around the world, with every timezone being a relative offset of UTC.

The result is in Unix Time, which is the number of milliseconds since the Unix Epoch (1st January 1970). This of course isn't of much use on its own, and is therefore used in conjuction with other [**DateTime**](README.md) **Nodes**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Offset (ms)`|**Int**|The offset from the current UTC in milliseconds.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`UTC Unix (ms)`|**Int**|The current UTC, with the offset (if any) applied.|

# See Also

- [**Now (UTC)**](now-utc.md)

# External Links

- [*UTC - The World's Time Standard*](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
- [*UTC Time Offsets*](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
- [*Epoch Unix Time Stamp Converter*](https://www.unixtimestamp.com/) on unixtimestamp.com.
- [*Current Millis*](https://currentmillis.com/) on currentmillis.com.