# Get PieStart

## Overview

![The Get PieStart Node.](../../../../.gitbook/assets/getpietstartupdatedimage.png)

The **Get PieStart Node** returns the starting _degree value_ of a **Pie Object** created in the **Scene Outliner Module** under **Vector**.

[**Scope**](../../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get PieStart Node Attributes.](../../../../.gitbook/assets/node-get-piestart-attr.png)

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
| `PieStart` | **Float** | The starting _degree value_. |

## See Also

* [**Set PieStart**](setpiestart.md)
* [**Set PieEnd**](setpieend.md)
* [**Get PieEnd**](getpieend.md)

