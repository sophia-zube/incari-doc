# Get PieEnd

## Overview

![The Get PieEnd Node.](../../../../.gitbook/assets/getpieend.png)

The **Get PieEnd Node** returns the ending _degree value_ of a **Pie Object** created in the **Scene Outliner Module** under **Vector**.

## Attributes

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
| `PieEnd` | **Float** | The ending _degree value_. |

## See Also

* [**Set PieStart**](setpiestart.md)
* [**Set PieEnd**](setpieend.md)
* [**Get PieStart**](getpiestart.md)

