# Get Position 2D (px)

## Overview

![The Get Position 2D (px) Node.](../../../.gitbook/assets/node-get-position-2d.png)

The **Get Position 2D (px) Node** returns the X and Y values of a **2D Object's** _position_.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

## Attributes

![The Get Position 2D (px) Node Attributes.](../../../.gitbook/assets/node-get-position-2d-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object** whose `Position` you wish to return, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Position` you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | A 2-dimensional **Vector** that contains the X and Y _position_ values of the target **Object**. |

## See Also

* [**Get Rotation 2D**](get-rotation-pixel.md)
* [**Get Size 2D (px)**](get-size-pixel.md)

