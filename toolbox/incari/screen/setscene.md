# Overview

![The Set Scene Node.](../../../.gitbook/assets/setscenenode.png)

The **Set Scene Node** sets the chosen **Scene** for a **Screen**.

# Attributes

![The Set Scene Node Attributes](../../../.gitbook/assets/setscenenodeattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Screen`|**Screen**|The ID of the desired **Screen**, if one is not already indicated in the **Input Socket**.|
|`Scene`|**Scene**|The ID of the desired **Scene**, if one is not already indicated in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Screen ID`|**Screen**|The ID of the desired **Screen**.|
|`Scene ID`|**Scene**|The ID of the desired **Scene**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scene ID`|**Scene**|The returned **Scene** ID.|



