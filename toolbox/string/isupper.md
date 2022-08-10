# Overview

![The IsUpper Node.](../../.gitbook/assets/isuppernode.png)

The **IsUpper Node** checks if a **String** is all uppercase and returns a **Bool** of either *True* or *False*. 

[**Scope**](../overview.md#scopes):
*  **Project**, **Scene**, **Function**, **Prefab**

# Attributes

![The IsUpper Node Attributes.](../../.gitbook/assets/isupperattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`String`|**String**|The **String** to be checked, if none is given in the **Input** **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`String`|**String**|The **String** to be checked.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`IsUpper`|**Bool**|Returns *True* or *False* depending on if the **String** is uppercase or not.|

# See Also

* [**IsLower**](islower.md)