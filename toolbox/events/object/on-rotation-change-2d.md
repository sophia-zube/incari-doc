# On Rotation Change 2D

## Overview

![The On Rotation Change 2D Node.](../../../.gitbook/assets/onrotationchange2dupdatedimage.png)

**On Rotation Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Rotation** of a **2D Object** changes.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On Rotation Change Node Attributes.](../../../.gitbook/assets/node-onrotationchange2d-attri.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **2D Object** in which a change of **Rotation** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **2D Object** in which a change of **Rotation** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Rotation` | **Vector2"** | The new **Rotation** of the **Object**. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |

## See Also

* [**Events**](../)
* [**Object**](./)
* [**Rotation**](../../../objects-and-types/attributes/common-attributes/transformation/README.md#rotation)
