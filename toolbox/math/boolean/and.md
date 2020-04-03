# AND

## Overview

![](../../../.gitbook/assets/node-and.png)

The **AND** is a _logical operator_ **Node** which takes two or more **Booleans** and returns a single **Boolean**.

The **Node** checks whether or not _all_ **Inputs** are _true_. If they are all true, then the `Output` **Value** will be true. If, however, a single one of the **Inputs** is _false_, `Output` will also be _false_.

| Input 1 | Input 2 | Output |
| :--- | :--- | :--- |
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Count` | **Int** | The number of **Data Input Sockets** the **Node** will have. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | **Bool** | The **Boolean Values** to be checked. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Bool** | Whether or not all of the **Inputs** are _true_. |

