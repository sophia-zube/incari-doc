# Overview

![The ScaleBy Action Node.](../../.gitbook/assets/scalebyaction.png)

**ScaleBy Action** moves an **Animation** by the numbers specified in `By` for the `Duration` (in seconds), in either **Attributes** or **Inputs**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Offset`|**Vector3**|???.|
|`Duration`|**Float**|The total time of the **Action**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Instance ID`| **InstanceID** | The assigned **Instance** of an **Animation**??.|
|(►) `Start`|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`Duration`|**Float**|The total time (in seconds).|
|`By`|**Vector3**|The amount to scale the **Animation** by within 3D space.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

# External Links

