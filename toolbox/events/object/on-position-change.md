# Overview

![The On Position Change Node.](../../../.gitbook/assets/node-on-position-change.png)

**On Position Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Position** of an **Object** changes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a change of **Position** triggers the **Logic Branch**.  |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Position` | **Vector3** | The new **Position** of the **Object**. |

# See Also

* [**Events**](../README.md)
* [**Object**](README.md)

