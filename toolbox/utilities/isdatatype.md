# Overview

![The Is Data Type Node.](../../.gitbook/assets/isfloattype.png)

The **Is Data Type Node** returns true or false depending on if the input **Variable** type matches the data type or not.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Dropdown**|The data type to compare the input type to. The **Node** name matches the `Data Type`, in the sample image this is **Float**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Variable**|The input **Object** to be compared.|
# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Bool**|Returns true or false depending on whether the input **Variable** type matches the data type.|



