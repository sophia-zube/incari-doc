# Overview

![The On Leap Motion Pinch Start Node.](../../../.gitbook/assets/onleapmotionpinchstartnode20241.png)

**On Leap Motion Pinch Start** is an **Event Listener** **Node** used for executing a **Logic Branch** when a *Leap Motion Pinch Action* starts.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Pinch Event` | **Dictionary** |Returns a **Dictionary** of the action's [properties](README.md#properties). |

# See Also

* [**On Leap Motion Pinch End**](on-leapmotion-pinch-end.md)
* [**On Leap Motion Pinch Update**](on-leapmotion-pinch-update.md)
