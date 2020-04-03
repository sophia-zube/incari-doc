# Root

## Overview

![](../../.gitbook/assets/node-root.png)

**Root** calculates the _nth root_ of a number. The _nth root_ \(`Output`\) of a number is the _base_ value, which when raised to the power of _n_ \(`Degree`\) would return the _radicand_ \(`Input`\).

The most common example of **Root** operations, is finding the square \(2nd\) root, or cubic \(3rd\) root of a number, however this can also be used for higher numbers.

| `Input` | `Degree` | `Output` |
| :--- | :--- | :--- |
| 9 | 2 | 3 |
| 13824 | 3 | 24 |
| 160000 | 4 | 20 |
| 1024 | 10 | 2 |

## Exponentiation-Related Nodes

The **Power**, **nth Root**, and **Logarithm** **Nodes** each relate to _exponentiation_. They all take two _known_ parameters and return the 3rd _unknown_ **Value**.

![](../../.gitbook/assets/exponential-functions.png)

## Attributes

_The **Root Node** has no **Attributes**_.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The **Value** which you want to find the _nth root_ of. |
| `Root` | **Float** | The degree of the exponentiation \(the "_n_" in "_nth root_"\). |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The _base_ number which, when multiplied against itself the number of times defined in `Root`, would return the **Value** of `Input`. |

## External Links

* [_Root_](https://www.mathopenref.com/root.html) on Math Open Reference.
* [_nth root_](https://en.wikipedia.org/wiki/Nth_root) on Wikipedia.

