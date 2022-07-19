# Overview

![The CrossFade Node.](../../.gitbook/assets/node-crossfade.png)

The **CrossFade** **Node** creates a transition between **Scenes** with a cross-fade.

# Attributes

![The CrossFade Node Attributes.](../../.gitbook/assets/node-crossfade-attri.png)

|Attribute|Type|Description|
|---|---|---|
| `Duration (sec)` | **Float** | The duration, in seconds, of the cross-fade, if none is given in the **Input Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|(►) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `In Scene` | **SceneID** | The **Scene** to which the current **Scene** will transition to. |
| `Screen` | **ScreenID** | The **Screen** that contains the initial and final **Scenes**. |
| `Duration` | **Float** | The duration, in seconds, of the cross-fade. |

# Outputs

|Output|Type|Description|
|---|---|---|
| `OnStart` (►) | **Pulse** | Flows to the next **Node** following **CrossFade** when the transition starts. |
| `OnEnd` (►) | **Pulse** | Flows to the next **Node** following **CrossFade** when the transition ends.  |


# See Also

* [**Fade**]()

