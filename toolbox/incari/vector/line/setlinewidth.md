# Set LineWidth

## Overview

![The Set LineWidth Node.](../../../../.gitbook/assets/node-set-linewidth.png)

The **Set LineWidth Node** sets the **LineWidth** of a **Line Object** created in the **Scene Outliner Module** under **Vector**.

[**Scope**](../../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Set LineWidth Node Attributes.](../../../../.gitbook/assets/node-set-linewidth-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `LineWidth` | **Int** | The **LineWidth** of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Get LineWidth**](getlinewidth.md)

