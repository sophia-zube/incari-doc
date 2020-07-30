# Overview

![The Get Array Element Node.](../../.gitbook/assets/toolbox/array/get-array-element.png)

**Get Array Element** is used for accessing elements in an **Array**. The **Node** accepts an **Array** and the *index/es* of the desired element/s in the **Array** and returns the desired element/s or the **Array** itself.

# Attributes
## Inputs/Outputs
The number of **Input** and **Output** **Element**s you wish to add to the **Attribute** section. Each **Element** represents an *index* element you wish to return.

|Attribute|Type|Description|
|---|---|---|
|`Default Index`|*Defined in the* `Data Type` ***Attribute***|The `Index` of the element you wish to return if no value is provided to the `Index` **Input** **Socket**.|
|`Data Type`|**Drop-down**|The `Data Type` of the `Index` element you wish to return.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Array`|**Array**|The desired element/s will be returned from this **Array**.|
|`Index`|*Defined in the* `Data Type` ***Attribute***|The `Index` of the element you wish to return.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Array`|**Array**|The **Array** provided to the **Input** **Socket**.|
|`Value`|*Defined in the* `Data Type` ***Attribute***.|The **Output** value accessed from the **Array**.|

# Eg Usage
![The Get Array Element Node.](../../.gitbook/assets/toolbox/array/get-array-element-usage.png)

# See Also
- [**Array Value**](array-value.md)

