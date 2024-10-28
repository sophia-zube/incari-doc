# Overview

![The Set Scene Environment Color Node.](../../.gitbook/assets/setsceneenvironmentcolornode20241.png)

The **Set Scene Environment Color Node** sets the color of a **Scene's** [`Environment Lighting`]((../../objects-and-types/project-objects/scene.md)) **Attribute** in the **Logic**.

[**Scope**](../overview.md#scopes): **Scene**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Scene ID`|**SceneID**|The ID of the **Scene** being referenced.|
|`Color`|**Color**|The color the user wishes to set as the `Environment Lighting`.|
|`Exposure`|**Float**|The exposure value, or how bright or dark the color appears. This can be from 0 to infinity.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Set Scene Environment Map**](setsceneenvironmentmap.md)

