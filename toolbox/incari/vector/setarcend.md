# Overview

![The Set ArcEnd Node.](../../../.gitbook/assets/setarcend.png)

The **Set ArcEnd Node** sets the ending *arc degree* of an **Object**, such as a **Vector Arc** created in the **Scene Outliner Module**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`ArcEnd`|**Float**|The ending *arc degree*.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Set ArcStart**](setarcstart.md)