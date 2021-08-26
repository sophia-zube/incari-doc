# Set ArcEnd

## Overview

![The Set ArcEnd Node.](../../../../.gitbook/assets/setarcend.png)

The **Set ArcEnd Node** sets the ending _arc degree_ of an **Arc Object** created in the **Scene Outliner Module** under _Vector_.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `ArcEnd` | **Float** | The ending _arc degree_. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Set ArcStart**](setarcstart.md)
* [**Get ArcStart**](getarcstart.md)
* [**Get ArcEnd**](getarcend.md)

