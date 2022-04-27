# On Position Change

## Overview

![The On Position Change Node.](../../../.gitbook/assets/onpositionchangenode.png)

**On Position Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Position** of an **Object** changes.

## Attributes

![The On Position Change Node Attributes.](../../../.gitbook/assets/onpositionchangeattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a change of **Position** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a change of **Position** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |


## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector3** | The new **Position** of the **Object**. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |

## See Also

* [**Events**](../)
* [**Object**](./)
* [**Position**](../../../getting-started/attributes/common-attributes/transformation.md#position)

