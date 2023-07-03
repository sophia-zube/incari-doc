# Overview

![The Merge To Stylesheet Node.](../../../.gitbook/assets/mergetostylesheet2.png)

The **Merge To Stylesheet Node** lets the user incorporate new data into the inputted [**Scene2D's**](../../../objects-and-types/project-objects/scene2d.md) stylesheet **Attribute**, without overwriting anything. It appends any new data to the end of the current stylesheet.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Scene ID`|**SceneID**|The **ID** of the desired **Scene2D** that will have its stylesheet merged with another.|
|`Stylesheet`|**String**|The *CSS* data that the user wishes to merge into the current stylesheet **Asset**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|


