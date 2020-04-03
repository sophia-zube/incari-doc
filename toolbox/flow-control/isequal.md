# Is Equal

## Overview

![](../../.gitbook/assets/node-isequal.png)

**IsEqual** is a **Relational Expression Node**, which compares two **Input Values**, and returns a **Boolean**, based on whether or not they are _equal_ to one another.

**Relational Expressions** are frequently used alongside **Branch Nodes** and **Logical Operator Nodes** to manipulate the flow of logic and are essential when building any complex applications.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `A` and `B` **Sockets**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `A` | _Defined in the_ `Data Type` **\*Attribute**.\* | The **Value** to be compared with `B`. |
| `B` | _Defined in the_ `Data Type` **\*Attribute**.\* | The **Value** to be compared with `A`. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `C` | **Bool** | Returns _true_ if `A` is equal to `B`. If not, then it returns _false_. |

## Examples

Below is an insight into the behaviour of the **IsEqual Node**. Note that when comparing **Strings**, the evaluation of equality is _case-sensitive_.

| `A` | `B` | `C` |
| :--- | :--- | :--- |
| 123 | 123 | _True_ |
| 85.05 | 85.06 | _False_ |
| "Cat" | "Dog" | _False_ |
| False | False | _True_ |
| "Mr. Smith" | "mr. smith" | _False_ |

## External Links

[_Relational operator_](https://en.wikipedia.org/wiki/Relational_operator) on Wikipedia.

