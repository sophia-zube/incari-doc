# RotateBy Action

## Overview

![The RotateBy Action Node.](../../.gitbook/assets/rotatebyactionupdatedimage.png)

The **RotateBy Action Node** continuously rotates an [**Object**](../../objects-and-types/scene-objects/README.md) by the *Euler angles* values specified in `Offset` for a given period of time, thus creating an **Animation**. Find an [example](#example) of how to use this **Node** and its effect over an **Object** at the end of this page.

Furthermore, visit the [**Actions Nodes**](README.md) page for a general introduction to these **Nodes**, and [**Rotation**](../../objects-and-types/attributes/common-attributes/transformation/README.md#rotation) for more detail about the `Rotation` **Attribute**.

[**Scope**](../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The RotateBy Action Node Attributes.](../../.gitbook/assets/rotatebyactionattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Offset` | **Vector3** | The amount to rotate the **Object** by, measured in *Euler angles* along the X, Y, and Z axes, if none is received in the `Offset` **Input Socket**.|
| `Duration (sec)` | **Float** | The total time of the **Action**, if none is received in the `Duration` **Input Socket**. |
| `Interpolation` | **Drop-down** | The `Interpolation` method to use for calculating the intermediate values of the *Euler Angles*. It can be [*Linear*](https://en.wikipedia.org/wiki/Linear_interpolation), [*Sine Ease In*](https://easings.net/#easeInSine), [*Sine Ease In Out*](https://easings.net/#easeInOutSine), or [*Sine Ease Out*](https://easings.net/#easeOutSine). |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**. |
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Duration` | **Float** | The total time \(in seconds\). |
| `Offset` | **Vector3** | The amount to rotate the **Object** by, measured in *Euler angles* along the X, Y, and Z axes. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**.  |
| `OnStart` \(►\) | **Pulse** | Flows to the next **Node** following **RotateBy Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to the next **Node** following **RotateBy Action** when the **Action** stops. |

## Example

This section shows a simple example of how to use the **RotateBy Action** **Node** and the effect it has on an **Object**. We start by [configuring the **Scene**](#scene-configuration), then [build the **Logic**](#logic), and finally show the [result](#final-result).

### Scene Configuration

We consider a [**Scene**](../../objects-and-types/project-objects/scene.md) with two [**Objects**](../../objects-and-types/scene-objects/README.md): a red [**Torus**](../../objects-and-types/scene-objects/primitives.md#torus) and a [**Directional Light**](../../objects-and-types/scene-objects/lights.md), both of which can be easily created in the [**Scene Outliner**](../../modules/scene-outliner.md). Then, we set the `Scale` **Attribute** of the **Torus** to $$(2, 2, 2)$$, its `Rotation` to $$(30, 30, 0)$$, and the `Position` of the **Light** to $$(0, 200, 0)$$. See this configuration in the following image:

![Scene configuration.](../../.gitbook/assets/examplesactions/ExampleRotateBy_1.png)

### Logic

We then need to configure the **Logic**. This is done in the [**Logic Editor**](../../modules/logic-editor.md).

We use first a [**Get Rotation** **Node**](../incari/object/get-rotation.md), which allows us to obtain an **Object's** current `Rotation` values, and then the **RotateFromTo Action** **Node**, to which we will feed the value previously obtained and configure it for it to *rotate* the **Object** from there to a fixed value of our choosing.

We use the **RotateBy Action** **Node** with the following **Attributes**: 

* `Offset`: $$(60, 60, 0)$$ 
* `Duration (sec)`: $$3$$ 
* `Interpolation`: `Linear`

And we connect to it the **Object Node** of the red **Torus** and a **Pulse** to the `Start` **Input Socket**. Thus, having the following **Logic** configuration:

![Logic configuration.](../../.gitbook/assets/examplesactions/ExampleRotateBy_2.png)

### Final result

Finally, the effect of the **RotateBy Action** **Node** when triggered is the following:

![Final result.](../../.gitbook/assets/examplesactions/ExampleRotateBy_3.gif)

## See Also

* [**RotateTo Action**](rotatetoaction.md)
* [**RotateFromTo Action**](rotatefromtoaction.md)

## External Links

* [_Rotation_](https://en.wikipedia.org/wiki/Rotation) on Wikipedia
* [_Euler angles_](https://en.wikipedia.org/wiki/Euler_angles) on Wikipedia

