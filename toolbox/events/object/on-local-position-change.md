# Overview

![The On Local Position Change Node.](../../../.gitbook/assets/onlocalpositionchange.png)

The **On Local Position Change Node** is an **Event Listener** 
**Node** used for executing a **Logic Branch** when the 
*local position* value of an **Object** changes. The **Node** subscribes to
the changes indefinitely until something external alters it.
 .

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Object** that has had its *local position* changed.|


# Inputs

|Input|Type|Description|
|---|---|---|
|`Object ID`|**ObjectID**| The ID of the target **Object** that had its *local position* changed.|
|`Subscribe` (►)|**Pulse**|The **Pulse** to be triggered by a previous action after a *local position* change. The resulting output will remain with each execution of the **On Local Position Change Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Rotation`|**Vector3**|The returned X, Y, and Z-axis values.|
|`Object ID`|**ObjectID**|The ID of the returned **Object**.|

# See Also


