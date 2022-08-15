# Get BackgroundColor

## Overview

![The Get BackgroundColor Node.](../../../.gitbook/assets/node-get-backgroundcolor.png)

The **Get BackgroundColor Node** returns the **BackgroundColor** of the target **Vector Object**. For example, this could be the **BackgroundColor** of an **Ellipse**, which can be created in the **Scene Outliner Module** under **Vector**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get BackgroundColor Node Attributes.](../../../.gitbook/assets/node-get-backgroundcolor-attr.png)

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
| `BackgroundColor` | **Color** | The **BackgroundColor** of the target **Object**. |

## See Also

* [**Set BackgroundColor**](setbackgroundcolor.md)

