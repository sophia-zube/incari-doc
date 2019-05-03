# Overview

![](../../../../.gitbook/assets/node-arc-tangent.png)

The **Arc Tangent Node** takes a single **Float Value**, representing an angle, in degrees (°) or radians (rad), and returns its *arc tangent*.

*Arc Tangent* is a *trigonometric function*, used to calculate the acute angles and side lengths of right-angled triangles. Trigonometry has a vast amount applications, ranging from engineering to astronomy. The most relevent to INCARI, though, is that it can be used to calculate cooridnates and distances within 3D space.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Is Degree`|**Bool**|Determines whether or not the `Input` **Value** is given in degrees (°) or radians (rad).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**|The angle to calculate the *arc tangent* of.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Float**|The *arc tangent* of `Input`.|

# External Links
- [*Trigonometry*](https://www.khanacademy.org/math/trigonometry) on Kahn Academy.
- [*Sine, Cosine and Tangent*](https://www.mathsisfun.com/sine-cosine-tangent.html) on Maths is Fun.