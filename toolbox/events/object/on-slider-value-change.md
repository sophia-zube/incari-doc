# Overview

![The On SliderValue Change Node.](../../../.gitbook/assets/onslidervaluenode20241.png)

The **On SliderValue Change Node** is an **Event Listener** **Node** used for executing a **Logic Branch** when the current value of a [**Slider Object**](../../../objects-and-types/scene2d-objects/gui/slider.md) changes.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**| The **Slider Object** in which a change of value triggers the **Logic Branch**.|
|`Subscribe` (►)|**Pulse**| An **Input Pulse** that needs to be triggered to start listening to the **Event**.  |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Value`|**String**| The new active value of the **Slider Object**.|
|`Object ID`|**ObjectID**|The ID of the given **Slider Object**.|

# See Also

* [**Get Slider Value**](../../incari/object/getslidervalue.md)

