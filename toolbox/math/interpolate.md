# Overview

![The Interpolate Node.](../../.gitbook/assets/node-interpolate.png)

**Interpolate** gradually changes the value of a numerical input from an initial value (`From`) to a target value (`To`) over a set period of time (`Duration (s)`).

By default, the value is adjusted *linearly*, but can also be interpolated using one of several of Incari's **Interpolation Types**.

Additionally, the interpolation can be executed a single time (`Once`) or multiple times (`Repeat`/`Alternate`) using the `Mode` **Attribute**.

{% tabs %}

{% tab title="Once" %}

`Once` means that the animation will play only once and then stop any further evaluation:

![](../../.gitbook/assets/interpolation-mode-once.gif)

{% endtab %}

{% tab title="Repeat" %}

`Repeat` repeats the interpolation a set number of times or indefinitely, depending on the `Count` and `Infinite` **Attributes**.

![](../../.gitbook/assets/interpolation-mode-repeat.gif)

{% endtab %}

{% tab title="Alternate" %}

`Alternate` interpolates forwards and then backwards a set number of times or indefinitely, depending on the `Count` and `Infinite` **Attributes**.

Also note that alternating interpolations will also reverse the interpolation `Type`. If it *eases in* from the start to end position, then it will *ease out* from the end, back to the start position.

![](../../.gitbook/assets/interpolation-mode-alternate.gif)

{% endtab %}

{% endtabs %}

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `From` and `To` **Sockets** and will return via its `Value` **Socket**.|
|`Duration (s)`|**Float**|The default value of `Duration (s)`, if no value is provided in the `Duration (s)` **Socket**.|
|`Interval Time (s)`|**Float**|The total amount of time that the value should be interpolated over per repetition (if any).|
|`From`|*Defined in the `Data Type` **Attribute***.|The default value of `From`, if no value is provided in the `From` **Socket**.|
|`To`|*Defined in the `Data Type` **Attribute***.|The default value of `To`, if no value is provided in the `To` **Socket**.|

## Interpolation

|Attribute|Type|Description|
|---|---|---|
|`Type`|**Drop-down**|The **Interpolation Type** that will be used to calculate the intermediate values between `To` and `From`.|
|`Mode`|**Drop-down**|Whether the interpolation should occur single or multiple times and the direction that subsequent interpolations should play.|
|`Count`|**Int**|The default value of `Count`, if no value is provided in the `Count` **Socket**.|
|`Infinite`|**Bool**|Whether or not to repeat/alternate the interpolation indefinitely.|

# Inputs

|Input|Type|Description|
|---|---|---|
|`Start`|**Pulse**|Initiates the interpolation.|
|`Duration (s)`|**Float**|The total time, in seconds, per interpolation.|
|`Count`|**Int**|How many times the interpolation will repeat/alternate. This is only applicable if `Mode` is not set to `Once` and `Infinite` is not set to *true*|
|`From`|*Defined in the `Data Type` **Attribute***.|The value at the start of the interpolation.|
|`To`|*Defined in the `Data Type` **Attribute***.|The value at the end of the interpolation.|
|`Reset`|**Pulse**|Used to prematurely stop the interpolation and halt all further evaluation.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|Triggers at a regular interval, defined in the `Interval Time (s)` **Attribute**, while the interpolation is running.|
|`Value`|*Defined in the `Data Type` **Attribute***.|The current value of the interpolation, which is updated periodically, while the interpolation is running.|
|`OnStart`|**Pulse**|An **Event** that triggers as soon as the *first* interpolation begins.|
|`OnReset`|**Pulse**|An **Event** that triggers as soon as the interpolation is manually rest using the `Reset` **Pulse Socket**.|
|`OnEnd`|**Pulse**|An **Event** that triggers as soon as the *last* interpolation ends.|