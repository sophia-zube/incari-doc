# Logarithm

## Overview

![](../../.gitbook/assets/node-logarithm.png)

**Logarithm** performs the inverse function of the **Power Node**. Rather than taking a _base_ **Value**, raising it to the power of an _exponent_, and returning the _power_, it takes the _base_ **Value**, along with the _power_, and returns the _exponent_.

## Exponentiation-Related Nodes

The **Power**, **nth Root**, and **Logarithm** **Nodes** each relate to _exponentiation_. They all take two _known_ parameters and return the 3rd _unknown_ **Value**.

![](../../.gitbook/assets/exponential-functions.png)

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Base` | **Drop-down** | A selection of common bases used in logarithm functions, which are: `2` \(binary\), `e` \(natural\) or `10` \(common\). |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The _power_ or _antilogarithm_ to be used, along with the _base_. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The _logarithm_ of the _base_ and _antilogarithm_. |

## External Links

* [_Logarithmic Functions_](https://www.sparknotes.com/math/precalc/exponentialandlogarithmicfunctions/section2/) on sparknotes.

