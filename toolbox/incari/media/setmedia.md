# Overview

![The Set Media Node.](../../../.gitbook/assets/setmedianode.png)

The **Set Media Node** applies a given **Media Asset** to an **Object**. This is only possible for **Video** and **Audio Assets**. These can be applied in the **Logic Editor** by dragging the desired **Asset** from the **Asset Database** (which can be populated with **Assets** by dragging them from the **Asset Mananger**).

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that the **Media Asset** will be set to.|
|`Media ID`|**MediaID**|The ID of the **Media Asset**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

[**Get Media**](getmedia.md)

