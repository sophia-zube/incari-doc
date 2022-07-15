# On Rotation Change

## Overview

![The On Rotation Change Node.](../../../.gitbook/assets/onrotationchangenode.png)

**On Rotation Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Rotation** of an **Object** changes.

## Attributes

![The On Rotation Change Node Attributes.](../../../.gitbook/assets/onrotationchangeattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a change of **Rotation** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a change of **Rotation** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Rotation` | **Vector3** | The new **Rotation** of the **Object**. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |


## See Also

* [**Events**](../)
* [**Object**](./)
* [**Rotation**](../../../objects-and-types/attributes/common-attributes/transformation.md#rotation)

