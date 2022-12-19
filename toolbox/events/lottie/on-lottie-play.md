# Overview

![The On Lottie Play Node.](../../../.gitbook/assets/node-on-lottie-play.png)

**On Lottie Play** is an **Event Listener** **Node** used for executing a **Logic Branch** when a *lottie* starts playing.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
| `Object ID` | **ObjectID** | **Lottie Sprite** that triggers the **Logic Branch** when played. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Object ID` | **ObjectID** | The **Lottie Sprite** received as **Input**. | 

# See Also

* [**Lottie Sprite**](../../../objects-and-types/scene-objects/lottie-sprite.md)
* [**Play Lottie**](../../incari/lottie/play-lottie.md)

# External Links

* [What is a Lottie?](https://lottiefiles.com/what-is-lottie) on LottieFiles.

