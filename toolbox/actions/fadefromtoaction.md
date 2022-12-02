# FadeFromTo Action

## Overview

![The FadeFromTo Action Node.](../../.gitbook/assets/fadefromtoactionupdatedimage.png)

The **FadeFromTo Action Node** continuously modifies the `Opacity` of an [**Object**](../../objects-and-types/scene-objects/README.md) over a specified period of time, thus creating an **Animation**. Both the initial and final values of the `Opacity` are chosen by the user. Find an [example](#example) of how to use this **Node** and its effect over an **Object** at the end of this page.

Furthermore, visit the [**Actions Nodes**](README.md) page for a general introduction to these **Nodes**.

[**Scope**](../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The FadeFromTo Action Node Attributes.](../../.gitbook/assets/fadefromtoactionattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `From` | **Float** | The desired initial value of the `Opacity`, if none is received in the `From` **Input Socket**. |
| `To` | **Float** | The desired final value of the `Opacity`, if none is received in the `To` **Input Socket**. |
| `Duration (sec)` | **Float** | The total time of the **Action**, if none is received in the `Duration` **Input Socket**. |
| `Interpolation` | **Drop-down** | The `Interpolation` method to use for calculating the intermediate values of the `Opacity`. It can be [*Linear*](https://en.wikipedia.org/wiki/Linear_interpolation), [*Sine Ease In*](https://easings.net/#easeInSine), [*Sine Ease In Out*](https://easings.net/#easeInOutSine), or [*Sine Ease Out*](https://easings.net/#easeOutSine). |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**. |
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Duration` | **Float** | The total time \(in seconds\). |
| `From` | **Float** | The initial value of the desired `Opacity`. |
| `To` | **Float** | The final value of the desired `Opacity`. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Action**. |
| `OnStart` \(►\) | **Pulse** | Flows to the next **Node** following **FadeFromTo Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to the next **Node** following **FadeFromTo Action** when the **Action** stops. |

## Example

This section shows a simple example of how to use the **FadeFromTo Action** **Node** and the effect it has on an **Object**. We start by [configuring the **Scene**](#scene-configuration), then [build the **Logic**](#logic), and finally show the [result](#final-result).

### Scene Configuration

We consider a [**Scene**](../../objects-and-types/project-objects/scene.md) with two [**Objects**](../../objects-and-types/scene-objects/README.md): a white arc over a black background, both of which can be easily created in the [**Scene Outliner**](../../modules/scene-outliner.md). Then, we set the `Size` **Attribute** of the arc to $$(500, 500, 0)$$ and the `Opacity` to $$0.25$$. See this configuration in the following image:

![Scene configuration.](../../.gitbook/assets/examplesactions/ExampleFadeFromTo_1.png)

### Logic

We then need to configure the **Logic**. This is done in the [**Logic Editor**](../../modules/logic-editor.md).

We use first a [**Get Opacity** **Node**](../incari/object/get-opacity.md), which allows us to obtain an **Object's** current `Opacity` value, and then the **FadeFromTo Action** **Node**, to which we will feed the value previously obtained and configure it for it to change it from there to a fixed value of our choosing.

For this purpose, we set the **Attributes** of the **FadeFromTo Action** **Node** in the following way:

* `To`: $$1$$ 
* `Duration (sec)`: $$1$$ 
* `Interpolation`: `Linear`

We just leave the `From` **Attribute** as it is, since this value will be obtained through the corresponding **Input Socket**.

Then, we connect the **Object ID** from the white arc [**Object Node**](../../objects-and-types/scene-objects/README.md#objects-in-the-logic) to the `Object ID` **Input Socket** of both **Nodes**, the `Opacity` **Output** from the **Get Opacity** **Node** to the `From` **Input Socket** in the **FadeFromTo** **Node**, and a **Pulse** through the **Get Opacity** **Node** and to the `Start` **Input** in **FadeFromTo**. Thus, having the following **Logic** configuration: 

![Logic configuration.](../../.gitbook/assets/examplesactions/ExampleFadeFromTo_2.png)

### Final result

Finally, the effect of the **FadeFromTo Action** **Node** when triggered is the following:

![Final result.](../../.gitbook/assets/examplesactions/ExampleFadeFromTo_3.gif)



## See Also

* [**FadeTo Action**](fadetoaction.md)

## External Links

* [_Transparency \(graphic\)_](https://en.wikipedia.org/wiki/Transparency_%28graphic%29) on Wikipedia.

