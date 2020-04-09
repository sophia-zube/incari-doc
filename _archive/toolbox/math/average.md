# Average

## Overview

![](../../.gitbook/assets/node-average.png)

**Average** takes two or more **Float Values** and calculates the _arithmetic mean_, which is the total _sum_ of the **Inputs** divided by the total _number_ of **Inputs**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Count` | **Int** | The number of **Data Input Sockets** the **Node** will have. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | **Float** | The **Values** that will be added together, and divided by `Count`. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The _arithmetic mean_ of all of the **Input Values**. |

## External Links

* [_Arithmetic Mean: What it is and How to Find it_](https://www.statisticshowto.datasciencecentral.com/arithmetic-mean/) on Statistics How To.

