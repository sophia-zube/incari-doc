# Maximum

## Overview

![](../../.gitbook/assets/node-maximum.png)

**Maximum** compares two or more numerical **Inputs** against each other and returns the upper bound \(maximum **Value**\) in the set.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The **Data Type** of all `Input` and `Output` **Sockets**. |
| `Count` | **Int** | The number of **Data Input Sockets** the **Node** will have. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | _Defined in the_ `Data Type` _**Attribute**_. | The **Values** to be compared against one another. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` _**Attribute**_. | The maximum **Value** in the set of **Inputs**. |

## External Links

* [_Upper and lower bounds_](https://en.wikipedia.org/wiki/Upper_and_lower_bounds) on Wikipedia.

