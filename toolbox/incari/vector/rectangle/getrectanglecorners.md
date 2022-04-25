# Get RectangleCorners

## Overview

![The Get RectangleCorners Node.](../../../../.gitbook/assets/node-get-rectanglecorners.png)

The **Get RectangleCorners Node** returns the **Corners** of a **Rectangle Object** created in the **Scene Outliner Module** under **Vector**. **Corners** are **Vector2** type **Variables**.

## Attributes

![The Get RectangleCorners Node Attributes.](../../../../.gitbook/assets/node-get-rectanglecorners-attr.png)

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
| `RectangleCorners` | **Vector2** | The **RectangleCorners** of the target **Object**. |

## See Also

* [**Set RectangleCorners**](setrectanglecorners.md)

