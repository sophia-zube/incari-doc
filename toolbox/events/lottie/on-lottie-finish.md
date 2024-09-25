# Overview

![The On Lottie Finish Node.](../../../.gitbook/assets/onlottiefinishnode20241.png)

**On Lottie Finish** is an **Event Listener** **Node** used for executing a **Logic Branch** when a *Lottie* finishes playing.

Note that this **Node** gets triggered when a *Lottie* animation is completed. For executing a **Logic Branch** when a *Lottie* animation is stopped, use [**On Lottie Stop**](on-lottie-stop.md).

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.



# Inputs

|Input|Type|Description|
|---|---|---|
| `Object ID` | **ObjectID** | **Lottie Sprite** that triggers the **Logic Branch** when it finishes. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Object ID` | **ObjectID** | The **Lottie Sprite** received as **Input**. | 


# See Also

* [**Lottie Sprite**](../../../objects-and-types/scene-objects/lottie-sprite.md)

# External Links

* [What is a Lottie?](https://lottiefiles.com/what-is-lottie) on LottieFiles.

