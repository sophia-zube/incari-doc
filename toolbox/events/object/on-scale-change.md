# Overview

![The On Scale Change Node.](../../../.gitbook/assets/node-on-scale-change.png)

**On Scale Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Scale** of an **Object** changes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a change of **Scale** triggers the **Logic Branch**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Scale` | **Vector3** | The new **Scale** of the **Object**. |

# See Also

* [**Events**](../README.md)
* [**Object**](README.md)
  

