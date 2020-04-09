# Switch

## Overview

![](../../.gitbook/assets/node-switch.png)

**Switch** compares whether or not the **Value** of a single **Data Input** is equal to any of multiple pre-defined **Values**, also known as **Cases**. Whichever **Case** is evaulated to be equal to the **Input**, will trigger the corresponding **Output Pulse**. If there are no matches found, the `Default` **Pulse** will be executed.

While you should never have **Cases** of the same **Value**, be aware that equality is checked from top-to-bottom; meaning that if a match has been found, subsequent **Cases** won't be evaluated.

### Attributes

_The **Switch Node** has no **Attributes**_.

### Inputs

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The type of data that will be plugged into the `Input` **Socket**. |

### Outputs

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Cases` | **List** | The pre-defined **Cases** to compare with `Input`. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | _Defined in the_ `Data Type` **\*Attribute**.\* | The **Value** to be compared with the list of pre-defined **Cases**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Case: [n]` | **Pulse** | An **Output Pulse** for each pre-defined **Case**, whose execution is triggered if the corresponding **Case** is evaluated as being equal to `Input`. |

## External Links

[_Switch statement_](https://en.wikipedia.org/wiki/Switch_statement) on Wikipedia.

