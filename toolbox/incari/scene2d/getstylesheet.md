# Overview

![The Get Stylesheet Node.](../../../.gitbook/assets/getstylesheetnode2.png)

The **Get Stylesheet Node** returns the stylesheet **Asset** of the inputted [**Scene2D**](../../../objects-and-types/project-objects/scene2d.md).

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Scene ID`|**SceneID**|The **ID** of the desired **Scene2D** that will have its stylesheet returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Stylesheet`|**String**|Returns the current stylesheet **Asset**.|



