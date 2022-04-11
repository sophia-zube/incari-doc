# Now \(UTC\)

## Overview

![The Now (UTC) Node.](../../.gitbook/assets/node-now-utc.png)

**Now \(UTC\)** is used for getting the current [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) in Unix Time.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Offset (ms)` | **Int** | The offset from the current UTC in milliseconds. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `UTC Unix (ms)` | **Int** | The current UTC, with the offset \(if any\) applied. |

## See Also

* [**DateTime**](./)
* [**Timezone Value**](timezone-value.md)

## External Links

* [_UTC - The World's Time Standard_](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
* [_UTC Time Offsets_](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
* [_Epoch Unix Time Stamp Converter_](https://www.unixtimestamp.com/) on unixtimestamp.com.
* [_Current Millis_](https://currentmillis.com/) on currentmillis.com.

