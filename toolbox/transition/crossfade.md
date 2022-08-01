# Overview

![The CrossFade Node.](../../.gitbook/assets/node-crossfade.png)

The **CrossFade** **Node** creates a **Transition** between **Scenes** with a cross-fade. It receives as inputs the **Scene** to **Transition** to, the **Screen** in which the **Transition** will take place, and the duration of the **Transition**.

*Scope*: **Project**

# Attributes

![The CrossFade Node Attributes.](../../.gitbook/assets/node-crossfade-attri.png)

|Attribute|Type|Description|
|---|---|---|
| `Duration (sec)` | **Float** | The duration, in seconds, of the cross-fade, if none is given in the **Input Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|(►) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `In Scene` | **SceneID** | The **Scene** to which the current **Scene** will **Transition** to. |
| `Screen` | **ScreenID** | The **Screen** that contains the initial and final **Scenes**. |
| `Duration` | **Float** | The duration, in seconds, of the cross-fade. |

# Outputs

|Output|Type|Description|
|---|---|---|
| `OnStart` (►) | **Pulse** | Flows to the next **Node** following **CrossFade** when the **Transition** starts. |
| `OnEnd` (►) | **Pulse** | Flows to the next **Node** following **CrossFade** when the **Transition** ends.  |


# See Also

* [**Fade**](fade.md)

