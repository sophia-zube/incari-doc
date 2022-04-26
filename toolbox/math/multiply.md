# Multiply

## Overview

![The Multiply Node.](../../.gitbook/assets/node-multiply2.png)

**Multiply** is a _basic arithmetic operation_ **Node** that outputs the product of all the values provided in the `Input` **Sockets**.

This is the equivalent of the multiplication \(`*` or `x`\) operation in computer science and mathematics.

## Attributes

![The Multiply Node Attributes.](../../.gitbook/assets/node-multiply2-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `Input` **Sockets**. |
| `Default Inputs` | _Defined in the `Data Type` **Attribute**_. | The amount of `Input` **Sockets** and their default values if they have no data connected to them. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | _Defined in the `Data Type` **Attribute**._ | The values to be multiplied together. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | _Defined in the `Data Type` **Attribute**._ | The product of all the values provided in the `Input` **Sockets**. |

