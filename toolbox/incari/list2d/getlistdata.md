# Overview

![The Get List Data Node.](../../../.gitbook/assets/getlistdata.png)

The **Get List Data Node** returns the *JSON* data of a **List** in **Array** format.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The desired **List** of the user.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`List Data`|**Array**|The *JSON* data from the desired **List** in **Array** format.|

# See Also

* [**Set List Data**](setlistdata.md)

