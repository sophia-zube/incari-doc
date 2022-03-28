# Overview

![The On On-Screen Keyboard Enter Pressed Node.](../../../.gitbook/assets/node-on-onscreen-keyboard-enter-pressed2.png)

The **On On-Screen Keyboard Enter Pressed** **Node** is an **Event Listener** **Node** used for executing a **Logic Branch** when `Enter` is pressed on an **On-Screen Keyboard**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object` | **ObjectID** | The **On-Screen Keyboard** in which the pressing of `Enter` triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **On-Screen Keyboard** in which the pressing of `Enter` triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Object ID` | **ObjectID** | The **On-Screen Keyboard** received as **Input**. |

# See Also

* [**On On-Screen Keyboard Input Changed**](on-onscreen-keyboard-input-changed.md)
* [**On On-Screen Keyboard Arrow Down Pressed**](ononscreenkeyboardarrowdownpressed.md)
* [**On On-Screen Keyboard Arrow Up Pressed**](ononscreenkeyboardarrowuppressed.md)
* [**On On-Screen Keyboard Key Pressed**](ononscreenkeyboardpressed.md)


