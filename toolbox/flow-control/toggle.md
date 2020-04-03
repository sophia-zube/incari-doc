# Toggle

## Overview

![](../../.gitbook/assets/node-toggle.png)

The **Toggle Node** holds an internal **Boolean Value**, which is toggled between _true_ and _false_, every time the **Node** is triggered.

A **Node** which holds data internally \(not held in a **Variable**\), is also referred to as having a **State**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Value` | **Bool** | The default **Value** of the **Node**, before it is executed. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `isOn` | **Bool** | Whether or not the **State** of the **Node** is currently set to _true_. |

