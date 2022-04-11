# ScaleTo Action

## Overview

![The ScaleTo Node.](../../.gitbook/assets/scaletoaction.png)

The **ScaleTo Action Node** scales an **Animation** to the absolute _scale_ values along the X, Y, Z axes specified in `To` for the `Duration` \(in seconds\), in either **Attributes** or **Inputs**. 

## Attributes

![The ScaleTo Node Attributes.](../../.gitbook/assets/scaletoactionattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `To` | **Vector3** | The desired _scale_ values along the X, Y, Z axes. |
| `Duration (sec)` | **Float** | The total time of the **Action**. |
| `Interpolation` | **Drop-down** | The `Interpolation` type. Can be Linear, Sine Ease In, Sine Ease Out, or Sine Ease In Out. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance** of an **Object**. |
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Duration` | **Float** | The total time \(in seconds\). |
| `To` | **Vector3** | The desired _scale_ values along the X, Y, Z axes. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance** of an **Object**. |
| `OnStart` \(►\) | **Pulse** | Flows to additional actions following **ScaleTo Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to additional actions following **ScaleTo Action** when the **Action** stops. |

## See Also

* [**ScaleBy**](scalebyaction.md)

## External Links

* [_Scaling \(geometry\)_](https://en.wikipedia.org/wiki/Scaling_%28geometry%29) on Wikipedia.

