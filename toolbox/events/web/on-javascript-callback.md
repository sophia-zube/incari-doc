# On Javascript Callback

## Overview

![The On Javascript Callback Node.](../../../.gitbook/assets/onjavascriptcallbacknode%20-%20Copy.png)

**On Javascript Callback** is an **Event Listener** **Node** used for executing a **Logic Branch** when a Javascript function is called. This function needs to be defined in the **Web Sprite** that is given as **Object** **Attribute**.

*Scope*: **Scene**, **Prefab**

## Attributes

![The On Javascript Callback Node.](../../../.gitbook/assets/javascriptcallbackattributes%20-%20Copy.png)

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | **Web Sprite** **Object** that contains the callback function, if none is given in the `Object ID` **Input Socket**. |

### Function

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `JS Function Name` | **String** | The name of the function that will trigger the **Logic**, if none is given in the `Function name` **Input Socket**. |

### Outputs

#### Data Types

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Types [n]` | **Drop-down** | Label and **Data Type** of the corresponding **Output** **Socket**. |


## Inputs

| Input | Type | Description |
| :--- | :--- | :---|
| `Object ID` | **ObjectID** |  **Web Sprite** **Object** that contains the callback function. |
| `Function name` | **String** | The name of the function that will trigger the **Logic**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |


## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Parameter` | _Defined in the `Data Type` **Attribute**_ | Parameter received by the callback function. |
| `Object ID` | **ObjectID** |**Web Sprite** **Object** received as **Input**. |

## See Also

* [**Call Javascript Function**](../../web/call-javascript-function.md)

