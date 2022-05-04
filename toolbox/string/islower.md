# Overview

![The IsLower Node.](../../.gitbook/assets/islowernode.png)

The **IsLower Node** checks if a **String** is all lowercase and returns a **Bool** of either *True* or *False*. 

# Attributes

![The IsLower Node Attributes.](../../.gitbook/assets/islowerattributes.png)

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
|`IsLower`|**Bool**|Returns *True* or *False* depending on if the **String** is lowercase or not.|

# See Also

* [**IsUpper**](isupper.md)
