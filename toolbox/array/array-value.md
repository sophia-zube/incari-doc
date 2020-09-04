# Overview

![The Array Value Node.](../../.gitbook/assets/toolbox/array/array-value.png)

**Array Value** is a data structure that can hold varying types of elements. The number of elements that the data structure can hold can be increased or decreased as needed. Also, each element can be identified and accessed by its index. 

# Attributes
## Inputs

### Inputs
The number of **Input Element**s you wish to add to the **Attribute section**. Each **Input Element** represents a value that is added to the **Array Value** **Node**. The values in this section are used if no values are provided to the **Input** **Node**. The format of the section is as follows: 

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The `Data Type` of the `Value` that you wish to add to the **Array Value** **Node**.|
|`Value`|*Defined in the* `Data Type` ***Attribute***.|A `value` that you wish to add to the **Array Value** **node**, if no value is provided in the input **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Array**.|A value you wish to add to the **Array Value** node.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Array**|An **Array** that holds the values that have been added to the **Array Value** **Node**.|

# Usage
![The Array Value Node Usage.](../../.gitbook/assets/toolbox/array/array-value-usage.png)

# See Also
[**Clear Array**](clear-array.md)

# External Links
[*Arrays*](https://en.wikipedia.org/wiki/Array_data_structure#:~:text=In%20computer%20science%2C%20an%20array,one%20array%20index%20or%20key.) on Wikipedia.
