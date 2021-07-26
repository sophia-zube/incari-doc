# Modulo

## Overview

![The Modulo Node.](../../.gitbook/assets/node-modulo.png)

**Modulo** is a _modular arithmetic_ **Node**, which divides one number \(_dividend_\) by a second number \(_divisor_\) and outputs the _remainder_ of the _Euclidean division_ operation.

This is the equivalent of the modulo \(`%`\) operation in computer science.

| `Dividend` | `Divisor` | Quotient | `Remainder` |
| :--- | :--- | :--- | :--- |
| 25 | 10 | 2 | 5 |
| 5.5 | 1.5 | 3 | 1 |
| 540 | 360 | 1 | 180 |
| 15 | 12 | 1 | 3 |

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `Input` **Sockets**. |
| `Default Dividend` | _Defined in the `Data Type` **Attribute**_. | The left side of the _Euclidean division_ operation \(the number to be divided\) if no value is provided in the `Dividend` **Socket**. |
| `Default Divisor` | _Defined in the `Data Type` **Attribute**_. | The right side of the _Euclidean division_ operation \(the number to divide by\) if no value is provided in the `Divisor` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Dividend` | _Defined in the `Data Type` **Attribute**_. | The left side of the  _Euclidean division_ operation \(the number to be divided\). |
| `Divisor` | _Defined in the `Data Type` **Attribute**_. | The right side of the _Euclidean division_ operation \(the number to divide by\). |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the _logic branch_, once this **Node** has finished its execution. |
| `Remainder` | _Defined in the `Data Type` **Attribute**._ | The remainder of the _Euclidean division_ operation. |

## External Links

* [_Intro to remainders_](https://www.khanacademy.org/math/arithmetic/arith-review-multiply-divide/arith-review-remainders/v/introduction-to-remainders) on Kahn Academy.
* [_What is modular arithmetic?_](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/what-is-modular-arithmetic) on Kahn Academy.

