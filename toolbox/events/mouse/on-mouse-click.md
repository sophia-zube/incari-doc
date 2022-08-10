# On Mouse Click

## Overview

![The On Mouse Click Node.](../../../.gitbook/assets/onmouseclicknode.png)

**On Mouse Click** is an **Event Listener** **Node** used for executing a **Logic Branch** when an **Object** is clicked.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Prefab**

## Attributes

![The On Mouse Click Node Attributes.](../../../.gitbook/assets/onmouseclickattributes.png)

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a click triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

### Button

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mouse Button` | **Drop-down** | Whether the left, middle, or right button of the mouse will trigger the **Logic**. |

## Inputs

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a click triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `IsLongClick` | **Bool** | _True_ when the button is pressed longer than usual. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

