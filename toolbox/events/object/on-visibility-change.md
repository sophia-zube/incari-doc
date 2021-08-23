# Overview

![The On Visibility Change Node.](../../../.gitbook/assets/node-on-visibility-change.png)

**On Visibility Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the **Visibility** of an **Object** changes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **Object** in which a change of **Visibility** triggers the **Logic Branch**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Is Visible` | **Bool** | Whether the **Object** is now visible or not. |

# See Also

* [**Events**](../README.md)
* [**Object**](README.md)
  

