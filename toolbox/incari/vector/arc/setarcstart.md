# Set ArcStart

## Overview

![The Set ArcStart Node.](../../../../.gitbook/assets/setarcstart.png)

The **Set ArcStart Node** sets the starting _arc degree_ of an **Arc Object** created in the **Scene Outliner Module** under _Vector_.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `ArcStart` | **Float** | The starting _arc degree_. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Set ArcEnd**](setarcend.md)
* [**Get ArcStart**](getarcstart.md)
* [**Get ArcEnd**](getarcend.md)

