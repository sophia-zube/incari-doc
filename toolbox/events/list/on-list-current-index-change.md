# On List Current Index Change

## Overview

![The On List Current Index Change Node.](../../../.gitbook/assets/node-on-list-current-index-change.png)

**On List Current Index Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the current index of a **List** changes.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **List** in which an index change triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Current Index` | **Int** | The current index of the **List**. |

## See Also

* [**List Events**](./)
* [**List Object**](../../../getting-started/scene-objects/list-widget.md)

