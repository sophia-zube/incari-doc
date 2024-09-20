# Overview

![The On Leap Motion Grab Start Node.](../../../.gitbook/assets/onleapmotiongrabstartnode20241.png)

**On Leap Motion Grab Start** is an **Event Listener** **Node** used for executing a **Logic Branch** when a *Leap Motion Grab Action* starts.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Grab Event` | **Dictionary** |Returns a **Dictionary** of the action's [properties](README.md#properties).  |

# See Also

* [**On Leap Motion Grab End**](on-leapmotion-grab-end.md)
* [**On Leap Motion Grab Update**](on-leapmotion-grab-update.md)
