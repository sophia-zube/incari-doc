# Overview

![The Is Media Playing Node.](../../../.gitbook/assets/ismediaplayingnode.png)

The **Is Media Playing Node** returns a **Boolean** value, depending on whether the inputted media is playing or not. Media in **Incari** is either a [**Video**](../../../objects-and-types/scene-objects/3dobjects/video.md) or an [**Audio**](../../../objects-and-types/scene-objects/audio.md). 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the media **Object** to be checked. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Is Playing` | **Bool** | Returns *true* if the media is playing, *false* if not.|


# See Also

* [**Pause Media**](pausemedia.md)
* [**Play Media**](playmedia.md)
* [**Stop Media**](stopmedia.md)
