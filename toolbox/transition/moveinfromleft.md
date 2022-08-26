# Overview

![The MoveInFromLeft Node.](../../.gitbook/assets/moveinfromleftnode.png)

The **MoveInFromLeft Node** applies a **Transition** to the chosen **Scene**. Starting off-screen, the chosen **Scene** moves in from the left of the **Screen**. This **Transition** leads to the chosen **Scene** covering the previous **Scene**, which remains static.  

[**Scope**](../overview.md#scopes): **Project**.

# Attributes

![The MoveInFromLeft Node Attributes**](../../.gitbook/assets/moveinfromleftattributes.png)

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
| `OnStart` (►) | **Pulse** | Flows to the next **Node** following **MoveInFromLeft** when the **Transition** starts. |
| `OnEnd` (►) | **Pulse** | Flows to the next **Node** following **MoveInFromLeft** when the **Transition** ends.  |

# See Also

* [**MoveInFromTop**](moveinfromtop.md)
* [**MoveinFromRight**](moveinfromright.md)
* [**MoveInFromBottom**](moveinfrombottom.md)
