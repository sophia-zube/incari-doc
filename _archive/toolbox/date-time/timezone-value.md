# Timezone Value

## Overview

![](../../.gitbook/assets/node-timezone-value.png)

**Timezone Value** returns the offset of a timezone, relative to [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) \(UTC\).

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Value` | **Drop-down** | The timezone which the offset is based on. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Timezone Offset (ms)` | **Int** | The offset of the timezone, in milliseconds, relative to UTC. |

## See Also

* [**Now \(UTC\)**](now-utc.md)

## External Links

* [_UTC - The World's Time Standard_](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
* [_UTC Time Offsets_](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
* [_Epoch Unix Time Stamp Converter_](https://www.unixtimestamp.com/) on unixtimestamp.com.
* [_Current Millis_](https://currentmillis.com/) on currentmillis.com.

