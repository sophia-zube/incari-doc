# Overview

![The On Alpha Change Node.](../../../.gitbook/assets/node-on-alpha-change.png)

**On Alpha Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Alpha** value of an **Object** changes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a change of the **Alpha** value triggers the **Logic Branch**.  |



# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Alpha` | **Float** | The modified **Alpha** value.  |

# See Also

* [**Events**](../README.md)
* [**Object**](README.md)
* [**Alpha**](../../../getting-started/attributes/common-attributes/sprite.md#alpha)

