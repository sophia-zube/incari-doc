# Set Rotation 2D

## Overview

![The Set Rotation 2D Node.](../../../.gitbook/assets/node-set-rotation-2d.png)

The **Set Rotation 2D Node** sets the _degree of rotation_ of a **2D Object**.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

## Attributes

![The Set Rotation 2D Node Attributes.](../../../.gitbook/assets/node-set-rotation-2d-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Rotation` | **Float** | The desired _degree of rotation_ of the **Object**, if one is not provided in the `Rotation` **Socket**. |
| `Object` | **ObjectID** | The target **Object** whose `Rotation` you wish to set, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Rotation` you wish to set. |
| `Rotation` | **Float** | The desired **Float** value you wish to set for the **Object's** `Rotation`. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Set Position 2D (px)**](set-position-pixel.md)
* [**Set Size 2D (px)**](set-size-pixel.md)

