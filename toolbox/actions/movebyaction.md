# MoveBy Action

## Overview

![The MoveBy Action Node.](../../.gitbook/assets/movebyactionupdatedimage.png)

The **MoveBy Action Node** continuously modifies the `Position` of an [**Object**](../../objects-and-types/scene-objects/README.md) by the values specified in `Offset` for a given period of time, thus creating an **Animation**. Find an [example](#example) of how to use this **Node** and its effect over an **Object** at the end of this page.

Furthermore, visit the [**Actions Nodes**](README.md) page for a general introduction to these **Nodes**, and [**Position**](../../objects-and-types/attributes/common-attributes/transformation/README.md#position) for more detail about the `Position` **Attribute**.

[**Scope**](../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The MoveBy Action Node Attributes.](../../.gitbook/assets/movebyactionattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Offset` | **Vector3** | The amount to modify the `Position` of an **Object** along the X, Y, Z axes, if none is given in the `Offset` **Input Socket**. |
| `Duration (sec)` | **Float** | The total time of the **Action**, if none is given in the `Duration` **Input Socket**. |
| `Interpolation` | **Drop-down** | The `Interpolation` method to use for calculating the intermediate values of the `Position`. It can be [*Linear*](https://en.wikipedia.org/wiki/Linear_interpolation), [*Sine Ease In*](https://easings.net/#easeInSine), [*Sine Ease In Out*](https://easings.net/#easeInOutSine), or [*Sine Ease Out*](https://easings.net/#easeOutSine). |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**.|
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Duration` | **Float** | The total time \(in seconds\). |
| `Offset` | **Vector3** | The amount to move the `Position` of an **Object** along the X, Y, Z axes. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**. |
| `OnStart` \(►\) | **Pulse** | Flows to the next **Node** following **MoveBy Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to the next **Node** following **MoveBy Action** when the **Action** stops. |

## Example

This section shows a simple example of how to use the **MoveBy Action** **Node** and the effect it has on an **Object**. We start by [configuring the **Scene**](#scene-configuration), then [build the **Logic**](#logic), and finally show the [result](#final-result).

### Scene Configuration

We consider a [**Scene**](../../objects-and-types/project-objects/scene.md) with two [**Objects**](../../objects-and-types/scene-objects/README.md): a red arc over a black background, both of which can be easily created in the [**Scene Outliner**](../../modules/scene-outliner.md). Then, we set the `Size` **Attribute** of the arc to $$(150, 150, 1)$$. See this configuration in the following image:

![Scene configuration.](../../.gitbook/assets/examplesactions/ExampleMoveBy_1.png)

### Logic

We then need to configure the **Logic**. This is done in the [**Logic Editor**](../../modules/logic-editor.md).

We use the **MoveBy Action** **Node** with the following **Attributes**: 

* `To`: $$(-200, -200, 0)$$ 
* `Duration (sec)`: $$3$$ 
* `Interpolation`: `Linear`

And we connect to it the **Object Node** of the red arc and a **Pulse** to the `Start` **Input Socket**. Thus, having the following **Logic** configuration:

![Logic configuration.](../../.gitbook/assets/examplesactions/ExampleMoveBy_2.png)

### Final result

Finally, the effect of the **ScaleTo Action** **Node** when triggered is the following:

![Final result.](../../.gitbook/assets/examplesactions/ExampleMoveBy_3.gif)


## See Also

* [**MoveTo Action**](movetoaction.md)

## External Links

* [_Position \(geometry\)_](https://en.wikipedia.org/wiki/Position_%28geometry%29) on Wikipedia.

