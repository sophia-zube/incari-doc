# Overview

![The Get PieStart Node.](../../../../.gitbook/assets/getpiestart.png)

The **Get PieStart Node** returns the starting *degree value* of a **Pie Object** created in the **Scene Outliner Module** under *Vector*.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`PieStart`|**Float**|The starting *degree value*.|

# See Also

* [**Get PieEnd**](getpieend.md)