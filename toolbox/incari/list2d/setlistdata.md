# Overview

![The Set List Data Node.](../../../.gitbook/assets/setlistdata.png)

The **Set List Data Node** allows the user to set the data of a **List** in a **Scene2D**. It requires that the *JSON* data is in **Array** format.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.



# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **List** that the user wishes to set the data for.|
|`List Data`|**Array**|The *JSON* list data in **Array** format.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get List Data**](getlistdata.md)