# Overview

![The Play ImageSequence Node.](../../../.gitbook/assets/playimagesequence.png)

The **Play ImageSequence Node** starts and plays through an **ImageSequence** at the specified timeframes. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Start Frame`|**Int**|The selected start frame. If -1, the start frame is the very first frame of the **ImageSequence**.|
|`End Frame`|**Int**| The selected end frame. If -1, the end frame is the very last frame of the **ImageSequence**.|
|`Object`|**ObjectID**|The target **Object**.|
|`PlayMode`|**Dropdown**|The `PlayMode` type. Can be either *Frames per Second* or *Time*.|
|`FPS`|**Int**|The number of *Frames per Second**.|
|`Interpolation Mode`|**Dropdown**|The `Interpolation Mode` type. Can be either *Constant* or *Linear*.| 
|`Loop Mode`|**Dropdown**|The looping type. Can be *Alternate*, *None*, or *Repeat*.|
|`PlayDirection`|**Dropdown**|The direction in which the **ImageSequence** plays. Can be `Backward` or `Forward`.|  

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|
|`Start Frame`|**Int**|The start frame.|
|`End Frame`|**Int**|The end frame.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Pause ImageSequence**](pauseimagesequence.md)
* [**Stop ImageSequence**](stopimagesequence.md)

