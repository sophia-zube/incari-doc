# On Scale Change

## Overview

![The On Scale Change Node.](../../../.gitbook/assets/onscalechangenode.png)

**On Scale Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Scale** of an **Object** changes.

## Attributes

![The On Scale Change Node Attributes.](../../../.gitbook/assets/onscalechangeattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a change of **Scale** triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a change of **Scale** triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Scale` | **Vector3** | The new **Scale** of the **Object**. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. |

## See Also

* [**Events**](../)
* [**Object**](./)
* [**Scale**](../../../objects-and-types/attributes/common-attributes/transformation.md#scale)

