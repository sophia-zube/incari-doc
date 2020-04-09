# Power

## Overview

![](../../.gitbook/assets/node-power.png)

**Power** performs an _exponentiation operation_, meaning that it multiplies the `Base` **Value**, against itself, _n_ times, with _n_ being defined by `Exponent`.

## Exponentiation-Related Nodes

The **Power**, **nth Root**, and **Logarithm** **Nodes** each relate to _exponentiation_. They all take two _known_ parameters and return the 3rd _unknown_ **Value**.

![](../../.gitbook/assets/exponential-functions%20%281%29.png)

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of **Data** that will be plugged into the `Base` and `Input` **Sockets**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Base` | _Defined in the_ `Data Type` **\*Attribute**.\* | The base **Value**, that will be multiplied against itself multiple times, based on the `Exponent`. |
| `Exponent` | _Defined in the_ `Data Type` **\*Attribute**.\* | The number of times, the `Base` **Value** will be multiplied against itself. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` **\*Attribute**.\* | The result of the exponentiation operation. |

## External Links

* [_Exponentiation: Definition & Examples_](https://study.com/academy/lesson/exponentiation-definition-examples-quiz.html) on Study.com.
* [_Exponentiation_](https://en.wikipedia.org/wiki/Exponentiation) on Wikipedia.

