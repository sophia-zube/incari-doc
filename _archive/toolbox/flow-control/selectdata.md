# Select Data

## Overview

![](../../.gitbook/assets/node-selectdata.png)

When you want to evaluate a **Data Value** in one or more different ways, depending on some conditions, **SelectData** is used to converge **Branches** of **Logic** into a single **Branch**, regardless of how the **Data** was calculated.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `Input` **Sockets**. |
| `Count` | **Int** | The number of **Input Pulses** and **Data Values** the **Node** will receive. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Pulse [n]` | **Pulse** | The **Pulse** corresponding to the **Data** in the **Socket** below. |
| `Input [n]` | _Defined in the_ `Data Type` _**Attribute**_. | The **Data Value** corresponding to the above **Pulse**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the_ `Data Type` _**Attribute**_. | The `Input` **Value** corresponding to whichever `Pulse` triggered the execution of the **Node**. |

## Examples

Below is a very simple example of the usage of the **SelectData Node**. We have two **OnKeyPress Nodes**, which increment/decrement the **Value** of a **Variable**, when the `Up` / `Down` arrows are pressed. By using **SelectData**, we only need to assing the **Value** once.

![](../../.gitbook/assets/example-selectdata.png)

