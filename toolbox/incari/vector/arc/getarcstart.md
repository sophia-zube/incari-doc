# Get ArcStart

## Overview

![The Get ArcStart Node.](../../../../.gitbook/assets/node-get-arcstart.png)

The **Get ArcStart Node** returns the starting _arc degree_ of an **Arc Object**.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

## Attributes

![The Get ArcStart Node Attributes.](../../../../.gitbook/assets/node-get-arcstart-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `ArcStart` | **Float** | The returned _arc degree_ of the **Object**. |

## See Also

* [**Set ArcStart**](setarcstart.md)
* [**Set ArcEnd**](setarcend.md)
* [**Get ArcEnd**](getarcend.md)

