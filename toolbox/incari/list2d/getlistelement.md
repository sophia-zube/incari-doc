# Overview

![The Get List Element Node.](../../../.gitbook/assets/getlistelementnode20241.png)

The **Get List Element Node** returns the element of a **List** at the specified `Index`. Each element consists of two parts: the icon and the text. 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The desired **List** of the user.|
|`Index`|**Int**|The index of the element the user wishes to return.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Icon Path`|**String**|The path on the user's local machine which locates the desired icon image to be returned.|
|`Text`|**String**|The text of the element to be returned.|

# See Also

* [**Set List Element**](setlistelement.md)

