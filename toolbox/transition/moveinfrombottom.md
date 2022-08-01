# Overview

![The MoveInFromBottom Node.](../../.gitbook/assets/node-moveinfrombottom.png)

The **MoveInFromBottom** **Node** creates a **Transition** from the current **Scene** to a chosen **Scene**. Starting off-screen, the chosen **Scene** moves in from the bottom of the **Screen**. This **Transition** leads to the chosen **Scene** covering the previous **Scene**, which remains static.  

*Scope*: **Project**

# Attributes

![The MoveInFromBottom Node Attributes**](../../.gitbook/assets/node-moveinfrombottom-attri.png)

|Attribute|Type|Description|
|---|---|---|
|`Duration (sec)`|**Float**| The duration, in seconds, of the **Transition**, if none is given in the **Input Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|`Start` (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `In Scene` | **SceneID** | The **Scene** to which the current **Scene** will **Transition** to. |
| `Screen` | **ScreenID** | The **Screen** that contains the initial and final **Scenes**. |
| `Duration` | **Float** | The duration, in seconds, of the **Transition**. |


# Outputs

|Output|Type|Description|
|---|---|---|
| `OnStart` (►) | **Pulse** | Flows to the next **Node** following **MoveInFromBottom** when the **Transition** starts. |
| `OnEnd` (►) | **Pulse** | Flows to the next **Node** following **MoveInFromBottom** when the **Transition** ends.  |

# See Also

* [**MoveInFromTop**](moveinfromtop.md)
* [**MoveInFromLeft**](moveinfromleft.md)
* [**MoveInFromRight**](moveinfromright.md)


