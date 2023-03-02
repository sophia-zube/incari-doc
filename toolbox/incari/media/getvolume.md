# Overview

![The Get Volume Node.](../../../.gitbook/assets/getvolume.png)

The **Get Volume Node** returns the current volume of a **Video Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The target **Video Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Volume`|**Int**|The integer value of the **Video's** volume.|

# See Also

* [**Set Volume**](setvolume.md)

