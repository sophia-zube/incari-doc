# Overview

![The On List Item Clicked Node.](../../../.gitbook/assets/onlistitemclicked.png)

The **On List Item Clicked Node** returns the index of the item that was clicked.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`List View`|**ObjectID**|The **ID** of the desired **List** whose item clicked will be returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Item Click`|**Int**|The index of the item clicked.|



