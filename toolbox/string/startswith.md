# Overview

![The StartsWith Node.](../../.gitbook/assets/startswithnode.png)

The **StartsWith Node** checks if a **String** starts with a *substring*, or `Pattern`, and returns a **Bool** of either *True* or *False*.

*Scope*: **Project**, **Scene**, **Function**, **Prefab**

# Attributes

![The StartsWith Node Attributes.](../../.gitbook/assets/startswithattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`String`|**String**|The **String** to be checked.|
|`Pattern`|**String**|The *substring* that will be compared to the start of the aforementioned **String**, if none is given in the **Input** **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`String`|**String**|The **String** to be checked.|
|`Pattern`|**String**|The *substring* that will be compared to the start of the aforementioned **String**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`StartsWith`|**Bool**|Returns *True* or *False* depending on whether the comparison is true or not.|

# See Also

* [**EndsWith**](endswith.md)

# External Links

* More on *substrings* on [Wikipedia](https://en.wikipedia.org/wiki/Substring).
