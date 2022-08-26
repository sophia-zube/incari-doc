# On List Load

## Overview

![The On List Load Node.](../../../.gitbook/assets/onlistloadnode.png)

**On List Load** is an **Event Listener** **Node** used for executing a **Logic Branch** when a **List** is loaded.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On List Load Node Attributes.](../../../.gitbook/assets/onlistloadattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **List** whose load triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Input 

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **List** whose load triggers the **Logic Branch**.
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Object ID` | **ObjectID** | The **List** received as **Input**. |

## See Also

* [**List Events**](./)
* [**List Object**](../../../objects-and-types/scene-objects/list-widget.md)

