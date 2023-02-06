# Overview

![The Stop Media Node.](../../../.gitbook/assets/stopmedianode.png)

The **Stop Media Node** can be used to stop a media **Object** already playing during the session. Media in **Incari** is either a **Video** or an **Audio**. 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the media **Object** to be played. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Is Media Playing**](ismediaplaying.md)
* [**Pause Media**](pausemedia.md)
* [**Play Media**](playmedia.md)
