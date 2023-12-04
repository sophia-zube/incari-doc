# Overview

![The Set Media Node.](../../../.gitbook/assets/setmedianode.png)

The **Set Media Node** applies a given **Media Asset** to a **Media Object**. This is only possible for **Video** and **Audio Assets**. These can be applied in the **Logic Editor** by dragging the desired **Asset** from the [**Asset Database**](../../../modules/asset-database.md) (which can be populated with **Assets** by dragging them from the [**Asset Manager**](../../../modules/asset-manager.md)).

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that the **Media Asset** will be set to.|
|`Media ID`|**MediaID**|The ID of the **Media Asset** that will be assigned to the **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get Media**](getmedia.md)
* [**Video**](../../../objects-and-types/scene-objects/3dobjects/video.md)
* [**Audio**](../../../objects-and-types/scene-objects/audio.md)

