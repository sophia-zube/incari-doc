# Overview

![The Get Scene Node.](../../../.gitbook/assets/getscenenode.png)

The **Get Scene Node** returns the **Scene** of a chosen **Screen**.

# Attributes

![The Get Scene Node Attributes](../../../.gitbook/assets/getscenenodeattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Screen`|**Screen**|The ID of the desired **Screen**, if none is indicated in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Screen ID`|**Screen**|The ID of the desired **Screen**.|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scene ID`|**Scene**|The returned ID of the **Screen's** **Scene**.|

# See Also

* [**Set Scene](setscene.md)
