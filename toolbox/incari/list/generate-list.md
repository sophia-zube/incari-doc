# Generate List

## Overview

![The Generate List Node.](../../../.gitbook/assets/generate-list.PNG)

**Generate List** accepts a **List** **Object** and renders it to a **Scene**.

## Attributes

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **List** **Object** you wish to generate, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The **List** **Object** you wish to generate. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**List**](https://github.com/cgi-studio-gmbh/incari-doc/tree/23ca004175ebe8c81ae3d4d6a0095a826c8d5f9a/getting-started/scene-objects/list-widget.md)
* [**Next List Entry**](next-list-entry.md)
* [**Previous List Entry**](previous-list-entry.md)
* [**Select List Entry**](select-list-entry.md)
* [**Set Active**](set-active.md)
* [**Set Current Index**](set-current-index.md)

