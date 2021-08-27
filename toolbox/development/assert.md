# Assert

## Overview

THIS IS A TEST.

![The Assert Node.](../../.gitbook/assets/node-assert.png)

The **Assert** **Node** compares two values and outputs the result of the comparison as a **Boolean**. The **Data Type** of the values to be compared can be chosen on the **Attributes**.

## Attributes

### Inputs

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The **Data Type** of the two values that will be compared. |
| `Operator` | **Drop-down** | The operation with which the values |
| `Default A` | _Defined in the `Data Type` **Attribute**_ | The default value of `A`, if none is received on the **Input Socket**. |
| `Default B` | _Defined in the `Data Type` **Attribute**_ | The default value of `B`, if none is received on the **Input Socket**. |
| `Label` | **String** | Message that will be printed on the console along with the test result. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `A` | _Defined in the `Data Type` **Attribute**_ | First value to compare. |
| `B` | _Defined in the `Data Type` **Attribute**_ | Second value to compare. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `C` | **Bool** | Result of the comparison. |

