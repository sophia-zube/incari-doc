# Overview

![The MoveInFromLeft Node.](../../.gitbook/assets/moveinfromleftnode.png)

The **MoveInFromLeft Node** applies a transition to the chosen **Scene**. Starting off-screen, the chosen **Scene** moves in from the left of the **Screen**. This **Transition** leads to the chosen **Scene** covering the previous **Scene**.  

# Attributes

![The MoveInFromLeft Node Attributes**](../../.gitbook/assets/moveinfromleftattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Duration (sec)`|**Float**|The duration, in seconds, of the transition, if none is given in the **Input Socket**. |


# Inputs

|Input|Type|Description|
|---|---|---|
|`Start` (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `In Scene` | **SceneID** | The **Scene** to which the current **Scene** will transition to. |
| `Screen` | **ScreenID** | The **Screen** that contains the initial and final **Scenes**. |
| `Duration` | **Float** | The duration, in seconds, of the transition. |


# Outputs

|Output|Type|Description|
|---|---|---|
| `OnStart` (►) | **Pulse** | Flows to the next **Node** following **MoveinFromLeft** when the transition starts. |
| `OnEnd` (►) | **Pulse** | Flows to the next **Node** following **MoveinFromLeft** when the transition ends.  |

# See Also

* [**MoveinFromRight**]()

