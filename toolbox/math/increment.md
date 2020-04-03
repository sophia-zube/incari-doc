# Increment

## Overview

![](../../.gitbook/assets/node-increment.png)

**Increment** increases an **Input Value** by a specified amount \(step\).

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be used for `Input`, `Output` and `Step`. |
| `Step` | _Defined in the_ `Data Type` _**Attribute**_. | The default amount to increment `Input` by, if there is nothing plugged into the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | _Defined in the_ `Data Type` _**Attribute**_. | The **Value** to be incremented. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` _**Attribute**_. | The incremented **Value**. |

