# Overview

![The On List Entry Select Node.]()

**On List Entry Select**  is an **Event Listener** **Node** used for executing a **Logic Branch** when an entry of a **List** is selected.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The **List** in which an entry select triggers the **Logic Branch**.  |



# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**| A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Selected Index` | **Int** | The index of the selected entry in the **List**. |

# See Also

* [**List Events**](README.md)
* [**List Object**](../../../getting-started/scene-objects/list-widget.md)

