# On Visibility Change

## Overview

![The On Visibility Change Node.](../../../.gitbook/assets/onvisibilitychangenode20241.png)

**On Visibility Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Visibility** of an **Object** changes.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On Visibility Change Node Attributes.](../../../.gitbook/assets/onvisibilitychangeattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a change of **Visibility** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a change of **Visibility** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Is Visible` | **Bool** | Whether the **Object** is now visible or not. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |
|`Event ID`| **ObjectID**| The ID of the current **Event**. This can be connected to the [**Unsubscribe Node**](../../incari/event/unsubscribe.md) to unsubscribe from the **Event**.|

## See Also

* [**Events**](../)
* [**Object**](./)

