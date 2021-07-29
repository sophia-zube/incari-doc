# Next List Entry

## Overview

![The Next List Entry Node.](../../../.gitbook/assets/next-list-entry.PNG)

**Next List Entry** selects the next entry item in a **List** **Object**.

## Attributes

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **List** **Object** which you wish to select the next entry item of. If an **Object** is provided in the `Object ID` **Socket**, this **Attribute** is not used. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The **List** **Object** which you wish to select the next entry item of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## Example Usage

![The Next List Entry Usage](../../../.gitbook/assets/next-list-entry.gif)

## See Also

* [**List**](https://github.com/cgi-studio-gmbh/incari-doc/tree/66656c2442958de634bc73f77b533a03f83df0fb/toolbox/incari/list/objects/scene-objects/list.md)
* [**Generate List**](generate-list.md)
* [**Previous List Entry**](previous-list-entry.md)

