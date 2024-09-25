# Overview

![The On Checkbox Value Change Node.](../../../.gitbook/assets/oncheckbox)

The **On Checkbox Value Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when the current **Boolean** value of a [**Toggle Object**](../../../objects-and-types/scene2d-objects/gui/toggle.md) changes.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**| The **Toggle Object** in which a change of **Boolean** value triggers the **Logic Branch**.|
|`Subscribe` (►)|**Pulse**| An **Input Pulse** that needs to be triggered to start listening to the **Event**.  |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Value`|**Boolean**| The new **Boolean** value of the **Toggle Object**.|
|`Object ID`|**ObjectID**|The ID of the given **Toggle Object**.|

# See Also

* [**Set CheckBox Value**](../../incari/object/set-checkbox-value.md)


