# On Javascript Callback

## Overview

![The On Javascript Callback Node.](../../../.gitbook/assets/node-on-javascript-callback.png)

**On Javascript Callback** is an **Event Listener** **Node** used for executing a **Logic Branch** when a Javascript function is called. This function needs to be defined in the **Web Sprite** that is given as **Object** **Attribute**.

## Attributes

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | **Web Sprite** **Object** that contains the callback function. |

### Function

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `JS Function Name` | **String** | The name of the function that will trigger the **Logic**.  |

### Outputs

#### Data Types

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Types [n]` | **Drop-down** | Label and **Data Type** of the corresponding **Output** **Socket**.  |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Parameter` | _Defined in the `Data Type` **Attribute**_ |  |



