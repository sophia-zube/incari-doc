# On Position Change 2D

## Overview

![The On Position Change 2D Node.](../../../.gitbook/assets/node-onpositionchange2d.png)

**On Position Change 2D** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Position** of a **2D Object** changes.

## Attributes

![The On Position Change 2D Node Attributes.](../../../.gitbook/assets/node-onpositionchange2d-attri.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **2D Object** in which a change of **Position** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **2D Object** in which a change of **Position** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |


## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | The new **Position** of the **Object**. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |


## See Also

* [**Events**](../)
* [**Object**](./)
* [**Position**](../../../objects-and-types/attributes/common-attributes/transformation/README.md#position)
