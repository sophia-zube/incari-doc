# Now \(UTC\)

## Overview

![](../../.gitbook/assets/node-now-utc.png)

**Now \(UTC\)** is used for getting the current [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) \(UTC\), which is a standard time basis around the world, with every timezone being a relative offset of UTC.

The result is in Unix Time, which is the number of milliseconds since the Unix Epoch \(1st January 1970\). This of course isn't of much use on its own, and is therefore used in conjuction with other [**DateTime**](https://github.com/cgi-studio-gmbh/incari-doc/tree/4112ceff668764a1a7a9bbd0c6554f8441406be4/logic-editor/toolbox/datetime/README.md) **Nodes**.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Offset (ms)` | **Int** | The offset from the current UTC in milliseconds. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `UTC Unix (ms)` | **Int** | The current UTC, with the offset \(if any\) applied. |

## See Also

* [**Now \(UTC\)**](now-utc.md)

## External Links

* [_UTC - The World's Time Standard_](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
* [_UTC Time Offsets_](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
* [_Epoch Unix Time Stamp Converter_](https://www.unixtimestamp.com/) on unixtimestamp.com.
* [_Current Millis_](https://currentmillis.com/) on currentmillis.com.

