# Overview

![The Set Array Element Node.](../../.gitbook/assets/toolbox/array/set-array-element.PNG)

**Set Array Element** updates element/s in an **Array** to new values.

# Attributes
## Inputs

### Inputs
The number of **Input Element**/s you wish to add to the **Attribute section**. The **Input Element**/s are used to update elements in the **Array** to new values. Each **Input Element** has the following format: 

|Attribute|Type|Description|
|---|---|---|
|`Index`|**Int**|The default `Index` of the element you wish to update if no value is provided in the `Index` **Input** **Socket**.|
|`Data Type`|**Drop-down**|The `Data Type` of the `Index` element you wish to update.|
|`Default Value`|*Defined in the* `Data Type` ***Attribute***.|The element whose `Index` is specified in the `Index` **Attribute** will be updated with this value.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Àrray`|**Array**|An **Array** whose element/s you wish to update.|
|`Index`|**Int**|The `Index` of the element you wish to update.|
|`Value`|*Defined in the* `Data Type` ***Attribute***.|An **Input** value that is used to replace the element whose *index* is specified in the `Index` **Input** **Socket**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Array`|**Array**|An **Output** **Array** whose element/s have been replaced with the desired values.|

# Eg Usage
![The Set Array Element Node Usage.](../../.gitbook/assets/toolbox/array/set-array-element-Usage.png)

# See Also
- [**Array Value**](array-value.md)
- [**Pop Array Element**](pop-array-element.md)

