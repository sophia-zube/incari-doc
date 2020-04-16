# Overview

![](../../.gitbook/assets/node-now-utc.png)

**Now (UTC)** is used for getting the current [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) in Unix Time.


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

- [**DateTime**](README.md)
- [**Timezone Value**](timezone-value.md)

# External Links

- [*UTC - The World's Time Standard*](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
- [*UTC Time Offsets*](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
- [*Epoch Unix Time Stamp Converter*](https://www.unixtimestamp.com/) on unixtimestamp.com.
- [*Current Millis*](https://currentmillis.com/) on currentmillis.com.