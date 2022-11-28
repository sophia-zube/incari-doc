# Previous List Entry

## Overview

![The Previous List Entry Node.](../../../.gitbook/assets/previouslistentryupdatedimage.png)

**Previous List Entry** selects the previous entry item in a **List** **Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Previous List Entry Node Attributes.](../../../.gitbook/assets/node-previous-list-entry-attr.png)

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **List** **Object** you wish to select the previous entry item of. If a **List** **Object** is provided in the `Object ID` **Socket**, this **Attribute** is not used. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The **List** **Object** you wish to select the previous entry item of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## Usage Example

![The Previous List Entry Usage.](../../../.gitbook/assets/previous-list-entry.gif)

## See Also

* [**List**](../../../objects-and-types/scene-objects/list-widget.md)
* [**Generate List**](generate-list.md)
* [**Next List Entry**](next-list-entry.md)

