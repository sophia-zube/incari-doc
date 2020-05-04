# Overview

![](../../../.gitbook/assets/node-arc-sine.png)

The **Arc Sine Node** takes a single **Float** value, representing an angle, in degrees (°) or radians (rad), and returns its *arcsine*.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Is Degree`|**Bool**|Determines whether or not the `Input` value is given in degrees (°) or radians (rad).|
|`Default Value`|**Float**|The default value of `Input`, if no value is provided in the `Input` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**|The angle to calculate the *arcsine* of.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|**Float**|The *arcsine* of `Input`.|

# See Also

- [**Trigonometry**](README.md)

# External Links
- [*Trigonometry*](https://www.khanacademy.org/math/trigonometry) on Kahn Academy.
- [*Sine, Cosine and Tangent*](https://www.mathsisfun.com/sine-Cosine-Tangent.html) on Maths is Fun.