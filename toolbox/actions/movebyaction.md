# Overview

![The MoveBy Action Node.](../../.gitbook/assets/movebyaction.png)

The **MoveBy Action Node** moves an **Animation** by the numbers specified in the `Offset` for the `Duration` (in seconds), in either **Attributes** or **Inputs**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Offset`|**Vector3**|The amount to move the **Animation** by within 3D space.|
|`Duration`|**Float**|The total time of the **Action**.|
|`Interpolation`|**Dropdown**|The `Interpolation` type. Can be Linear, Sine Ease In, Sine Ease Out, or Sine Ease In Out.|

# Inputs

|Input|Type|Description|
|---|---|---|
|`Instance ID`| **InstanceID** | The assigned **Instance** of an **Animation**??.|
|(►) `Start`|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`Duration`|**Float**|The total time (in seconds).|
|`Offset`|**Vector3**|The amount to move the **Animation** by within 3D space.|

# Outputs

|Output|Type|Description|
|---|---|---|
|`Instance ID`|**InstanceID**|The assigned **Instance** of an **Animation**??.|
|`OnStart` (►)|**Pulse**|Flows to additional actions following **MoveBy Action** if the **Action** is executed.|
|`OnEnd` (►)|**Pulse**|Flows to additional actions following **MoveBy Action** if the **Action** stops.|

# See Also

* [**MoveTo Action**](movetoaction.md)

# External Links

* [*Position (geometry)*](https://en.wikipedia.org/wiki/Position_(geometry)) on Wikipedia. 