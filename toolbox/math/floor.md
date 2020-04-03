# Floor

## Overview

![](../../.gitbook/assets/node-floor.png)

**Floor** takes a numerical **Value** and returns the highest whole number, which is less than, or equal to, the `Input` **Value**. This basically means that the **Value** is rounded down, with anything after the decimal point of a number, being removed, making it a non-fractional number.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The **Data Type** of the `Input` and `Output` **Sockets**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | _Defined in the_ `Data Type` **\*Attribute**.\* | The **Value** to be _rounded down_ to 0 decimal places. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` **\*Attribute**.\* | The **Value** of `Input` after being _rounded down_ to 0 decimal places. |

## External Links

* [_Floor and Ceiling Functions_](https://www.mathsisfun.com/sets/function-floor-ceiling.html) on Maths is Fun.

