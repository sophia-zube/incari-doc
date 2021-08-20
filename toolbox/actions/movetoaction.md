# Overview

![The MoveTo Action Node.](../../.gitbook/assets/movetoaction.png)

The **MoveTo Action Node** moves an **Animation** to the absolute coordinates specified in the `To` for the `Duration` (in seconds), in either **Attributes** or **Inputs**. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`To`|**Vector3**|The desired *position* along the X, Y, Z axes.|
|`Duration (sec)`|**Float**|The total time of the **Action**.|
|`Interpolation`|**Dropdown**|The `Interpolation` type. Can be Linear, Sine Ease In, Sine Ease Out, or Sine Ease In Out.|

# Inputs

|Input|Type|Description|
|---|---|---|
|`Instance ID`| **InstanceID** | The assigned **Instance** of an **Object**.|
|(►) `Start`|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`Duration`|**Float**|The total time (in seconds).|
|`To`|**Vector3**|The desired *position* along the X, Y, Z axes.|

# Outputs

|Output|Type|Description|
|---|---|---|
|`Instance ID`|**InstanceID**|The assigned **Instance** of an **Object**.|
|`OnStart` (►)|**Pulse**|Flows to additional actions following **MoveTo Action** when the **Action** starts.|
|`OnEnd` (►)|**Pulse**|Flows to additional actions following **MoveTo Action** when the **Action** stops.|

# See Also

* [**MoveBy Action**](movebyaction.md)

# External Links

* [*Position \(geometry\)*](https://en.wikipedia.org/wiki/Position_(geometry)) on Wikipedia. 