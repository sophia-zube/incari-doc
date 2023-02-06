# On Media Play

## Overview

![The On Media Play Node.](../../../.gitbook/assets/onmediaplay.png)

**On Media Play** is an **Event Listener Node** that gives the user a way to perform an action once a media **Object** starts, such as a **Video** fading to black. Media in **Incari** is either a **Video** or **Audio**. 

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


## Inputs

| Input | Type | Description |
|:---|:---|:---|
|`Object ID` | **ObjectID** | The media **Object** that triggers the **Logic Branch** on playing. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |



## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Object ID` | **ObjectID** | The media **Object** received as **Input**. |

## See Also

* [**On Media Finish**](onmediafinish.md)

