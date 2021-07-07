# Is Equal

## Overview

![](../.gitbook/assets/node-is-equal.png)

**Is Equal** is a _relational expression_ **Node**, which compares two input values, and returns a **Boolean**, based on how the two values compare to each other in terms of _equality_. The **Node** has two modes, determined by the `Mode` **Attribute**:

1. `IsEqual` - Are the two values equal in value.
2. `IsNotEqual` - Are the two values _not_ equal in value.

_Relational expressions_ are frequently used in combination with **Branch Nodes** and _logical operator_ **Nodes** \(**AND**, **OR**, and **Negate**\) to create _conditional logic_, and are essential for building complex systems.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `A` and `B` **Sockets**. |
| `Mode` | **Drop-down** | The type of expression that will be used when comparing the values. |
| `Default Value A` | _Defined in the `Data Type` **Attribute**._ | The value of `A` if no value is provided via the **Node**'s **Socket**. |
| `Default Value B` | _Defined in the `Data Type` **Attribute**._ | The value of `B` if no value is provided via the **Node**'s **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `A` | _Defined in the `Data Type` **Attribute**._ | The value to be compared with `B`. |
| `B` | _Defined in the_ `Data Type` _**Attribute**_ | The value to be compared with `A`. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the _logic branch_, once this **Node** has finished its execution. |
| `C` | **Bool** | Returns _true_ if `A` is equal to `B`. If not, then it returns _false_. |

## External Links

[_Relational operator_](https://en.wikipedia.org/wiki/Relational_operator) on Wikipedia.

