# Overview

![The On On-Screen Keyboard Input Changed Node.](../../../.gitbook/assets/ononscreenkeyboardinputchangednode.png)

The **On On-Screen Keyboard Enter Pressed** **Node** is an **Event Listener** **Node** used for executing a **Logic Branch** when the input of an **On-Screen Keyboard** is changed.

*Scope*: **Scene**, **Prefab**

# Attributes

![The On On-Screen Keyboard Input Changed Node Attributes.](../../../.gitbook/assets/ononscreenkeyboardinputchangedattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Object` | **ObjectID** | The **On-Screen Keyboard** in which an input change triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

|Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **On-Screen Keyboard** in which an input change triggers the **Logic Branch** |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Keyboard Input` | **String** | The input of the **On-Screen Keyboard**. |
| `Object ID` | **ObjectID** | The **On-Screen Keyboard** received as **Input**. |

# See Also

* [**On On-Screen Keyboard Enter Pressed**](on-onscreen-keyboard-enter-pressed.md)
* [**On On-Screen Keyboard Arrow Down Pressed**](ononscreenkeyboardarrowdownpressed.md)
* [**On On-Screen Keyboard Arrow Up Pressed**](ononscreenkeyboardarrowuppressed.md)
* [**On On-Screen Keyboard Key Pressed**](ononscreenkeyboardpressed.md)