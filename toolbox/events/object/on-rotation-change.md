# Overview

![The On Rotation Change Node.](../../../.gitbook/assets/node-on-rotation-change.png)

**On Rotation Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Rotation** of an **Object** changes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a change of **Rotation** triggers the **Logic Branch**.  |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Rotation` | **Vector3** | The new **Rotation** of the **Object**.  |


# See Also

* [**Events**](../README.md)
* [**Object**](README.md)


