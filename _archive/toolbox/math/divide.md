# Divide

## Overview

![](../../.gitbook/assets/node-divide.png)

**Divide** divides all of the values provided in the **Input Sockets**, in order, from top-to-bottom, and returns the result of those operations.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of **Data** that will be plugged into the `Input` **Sockets**. |
| `Count` | **Int** | The number of **Data Input Sockets** the **Node** will have. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | _Defined in the_ `Data Type` _**Attribute**_. | The **Values** to be divided. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` _**Attribute**_. | The result of the division operation\(s\). |

