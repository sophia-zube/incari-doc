# Overview

![The Unload Scene Node.](../../../.gitbook/assets/unloadscenenode20241.png)

The **Unload Scene Node** unloads the specified **Scene** and returns a **Boolean** which confirms or denies this success.

Please note that **Scene Separation** must be enabled in the [**Project Settings**](../../../modules/project-settings/sceneseparation.md).

[**Scope**](../../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Scene ID`|**SceneID**|The ID of the chosen **Scene** that will be loaded.|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Success`|**Boolean**|Returns *true* if the **Scene** was successfully unloaded, or *false* if not.|

# See Also

* [**Load Scene**](loadscene.md)

