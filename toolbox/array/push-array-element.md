# Overview

![The Push Array Element Node.](../../.gitbook/assets/toolbox/array/push-array-element.png)

**Push Array Element** adds element/s to an **Array**. The **Array** is given as input to the **Node**.

# Attributes
## Inputs

### Inputs
The number of **Input** **Elements** you wish to add to the **Attribute** section. The **Elements** added to the **Attribute** section will also be added to the **Input** **Array**. Each **Element** has the following format:

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The `Data Type` of the element you wish to add the **Input** **Array**.|
|`Default Value`|*Defined in the* `Data Type` ***Attribute***.|A `Default Value` you wish to add to the **Array** if no value is provided to the **Input** **Socket**.|

## Mode
The `Mode` is a *toggle* that determines if an element will be added to the *front* or *back* of the **Array**.

|Attribute|Type|Description|
|---|---|---|
|`Add to end`|**Bool**|If the *toggle* is switched on, the desired element is added to the *back* of the **Array** otherwise it will be added to the *front* of the **Array**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Array (optional)`|**Array**|An **Array** whose contents you wish to add to a desired **Array**.|
|`Value`|*Defined in the* `Data Type` ***Attribute***|The value you wish to add to a desired **Array**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Array`|**Array**|The resulting **Array** after the desired values are successfully added.|

# See Also
- [**Array Value**](array-value.md)
- [**Pop Array Element**](pop-array-element.md)

