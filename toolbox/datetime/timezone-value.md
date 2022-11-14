# Timezone Value

## Overview

![The Timezone Value Node.](../../.gitbook/assets/timezonevalueupdatedimage.png)

**Timezone Value** returns the offset of a timezone, relative to [Coordinated Universal Time](https://www.timeanddate.com/time/aboututc.html) \(UTC\).

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

## Attributes

![The Timezone Value Node Attributes.](../../.gitbook/assets/node-timezone-value-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Value` | **Drop-down** | The timezone that will be used, which is an offset of the UTC. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Timezone Offset (ms)` | **Int** | The offset from the UTC in milliseconds. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Timezone Offset (ms)` | **Int** | The offset of the timezone, in milliseconds, relative to UTC. |

## See Also

* [**DateTime**](./)
* [**Now \(UTC\)**](https://docs.incari.com/incari-studio/toolbox/datetime/now-utc)

## External Links

* [_UTC - The World's Time Standard_](https://www.timeanddate.com/time/aboututc.html) on timeanddate.com.
* [_UTC Time Offsets_](https://www.utctime.net/utc-time-zone-offsets) on utctime.net.
* [_Epoch Unix Time Stamp Converter_](https://www.unixtimestamp.com/) on unixtimestamp.com.
* [_Current Millis_](https://currentmillis.com/) on currentmillis.com.

