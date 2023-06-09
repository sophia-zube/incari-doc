# RotateFromTo Action

This **Node** has different versions for [**Scenes**](../../../objects-and-types/project-objects/scene.md) and [**Scene2Ds**](../../../objects-and-types/project-objects/scene2d.md). Find in the tabs below the documentation for both versions.

{% tabs %}
{% tab title="Scene" %}

## Overview

![The RotateFromTo Action Node.](../../.gitbook/assets/rotatefromtoactionupdatedimage.png)

The **RotateFromTo Action Node** continuously rotates a [**Scene Object**](../../objects-and-types/scene-objects/) from the _Euler angles_ specified in `From` to those specified in `To` for a given period of time, thus creating an **Animation**. <!--Find an [example](rotatefromtoaction.md#example) of how to use this **Node** and its effect over an **Object** at the end of this page.-->

Furthermore, visit the [**Actions Nodes**](./) page for a general introduction to these **Nodes**, and [**Rotation**](../../objects-and-types/attributes/common-attributes/transformation/#rotation) for more detail about the `Rotation` **Attribute**.

[**Scope**](../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The RotateFromTo Action Node Attributes.](../../.gitbook/assets/rotatefromtoactionattributes.png)

| Attribute        | Type          | Description                                                                                                                                                                                                                                                                                                                                      |
| ---------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `From`           | **Vector3**   | The _Euler angles_ along the X, Y, and Z axes to rotate from, if none are received in the `From` **Input Socket**.                                                                                                                                                                                                                               |
| `To`             | **Vector3**   | The _Euler angles_ along the X, Y, and Z axes to rotate to, if none are received in the `To` **Input Socket**.                                                                                                                                                                                                                                   |
| `Duration (sec)` | **Float**     | The total time of the **Action**, if none is received in the `Duration` **Input Socket**.                                                                                                                                                                                                                                                        |
| `Interpolation`  | **Drop-down** | The `Interpolation` method to use for calculating the intermediate values of the _Euler Angles_. It can be [_Linear_](https://en.wikipedia.org/wiki/Linear\_interpolation), [_Sine Ease In_](https://easings.net/#easeInSine), [_Sine Ease In Out_](https://easings.net/#easeInOutSine), or [_Sine Ease Out_](https://easings.net/#easeOutSine). |

## Inputs

| Input         | Type           | Description                                                                                                                                  |
| ------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](./#instance-id) of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**. |
| (►) `Start`   | **Pulse**      | A standard **Input Pulse**, to trigger the execution of the **Node**.                                                                        |
| `Object ID`   | **ObjectID**   | The ID of the target **Object**.                                                                                                             |
| `Duration`    | **Float**      | The total time (in seconds).                                                                                                                 |
| `From`        | **Vector3**    | The _Euler angles_ along the X, Y, and Z axes to rotate from.                                                                                |
| `To`          | **Vector3**    | The _Euler angles_ along the X, Y, and Z axes to rotate to.                                                                                  |

## Outputs

| Output        | Type           | Description                                                                              |
| ------------- | -------------- | ---------------------------------------------------------------------------------------- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](./#instance-id) of the **Action**.                        |
| `OnStart` (►) | **Pulse**      | Flows to the next **Node** following **RotateFromTo Action** when the **Action** starts. |
| `OnEnd` (►)   | **Pulse**      | Flows to the next **Node** following **RotateFromTo Action** when the **Action** stops.  |

{% tab title="Scene2D" %}

## Overview

![The RotateFromTo Action Node.](../../.gitbook/assets/rotatefromtoactionnode2d.png)

The **RotateFromTo Action Node** continuously rotates a [**Scene2D Object**](../../objects-and-types/scene-objects/) from the value specified in `From` to that specified in `To` for a given period of time, thus creating an **Animation**. <!--Find an [example](rotatefromtoaction.md#example) of how to use this **Node** and its effect over an **Object** at the end of this page.-->

Furthermore, visit the [**Actions Nodes**](./) page for a general introduction to these **Nodes**, and [**Rotation**](../../objects-and-types/attributes/common-attributes/transformation/#rotation) for more detail about the `Rotation` **Attribute**.

[**Scope**](../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The RotateFromTo Action Node Attributes.](../../.gitbook/assets/rotatefromtoactionatts2d.png)

| Attribute        | Type          | Description                                                                                                                                                                                                                                                                                                                                      |
| ---------------- | ------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| `From`           | **Float**   | The value to rotate from, if none are received in the `From` **Input Socket**.                                                                                                                                                                                                                               |
| `To`             | **Float**   | The value to rotate to, if none are received in the `To` **Input Socket**.                                                                                                                                                                                                                                   |
| `Duration (sec)` | **Float**     | The total time of the **Action**, if none is received in the `Duration` **Input Socket**.                                                                                                                                                                                                                                                        |
| `Interpolation`  | **Drop-down** | The `Interpolation` method to use for calculating the intermediate values of the _Euler Angles_. It can be [_Linear_](https://en.wikipedia.org/wiki/Linear\_interpolation), [_Sine Ease In_](https://easings.net/#easeInSine), [_Sine Ease In Out_](https://easings.net/#easeInOutSine), or [_Sine Ease Out_](https://easings.net/#easeOutSine). |

## Inputs

| Input         | Type           | Description                                                                                                                                  |
| ------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------------- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](./#instance-id) of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**. |
| (►) `Start`   | **Pulse**      | A standard **Input Pulse**, to trigger the execution of the **Node**.                                                                        |
| `Object ID`   | **ObjectID**   | The ID of the target **Object**.                                                                                                             |
| `Duration`    | **Float**      | The total time (in seconds).                                                                                                                 |
| `From`        | **Float**    | The value to rotate from.                                                                                |
| `To`          | **Float**    | The value to rotate to.                                                                                  |

## Outputs

| Output        | Type           | Description                                                                              |
| ------------- | -------------- | ---------------------------------------------------------------------------------------- |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](./#instance-id) of the **Action**.                        |
| `OnStart` (►) | **Pulse**      | Flows to the next **Node** following **RotateFromTo Action** when the **Action** starts. |
| `OnEnd` (►)   | **Pulse**      | Flows to the next **Node** following **RotateFromTo Action** when the **Action** stops.  |

{% endtab %}
{% endtabs %}

## Example

This section shows a simple example of how to use the **RotateFromTo Action** **Node** and the effect it has on a **Scene Object**. This concept can be applied as well to a **Scene2D Object**. 

We start by [configuring the **Scene**](rotatefromtoaction.md#scene-configuration), then [build the **Logic**](rotatefromtoaction.md#logic), and finally show the [result](rotatefromtoaction.md#final-result).

### Scene Configuration

We consider a [**Scene**](../../objects-and-types/project-objects/scene.md) with two [**Objects**](../../objects-and-types/scene-objects/): a red [**Torus**](../../objects-and-types/scene-objects/primitives.md#torus) and a [**Directional Light**](../../objects-and-types/scene-objects/lights.md), both of which can be easily created in the [**Scene Outliner**](../../modules/scene-outliner.md). Then, we set the `Scale` **Attribute** of the **Torus** to $$(2, 2, 2)$$, its `Rotation` to $$(30, 30, 0)$$, and the `Position` of the **Light** to $$(0, 200, 0)$$. See this configuration in the following image:

![Scene configuration.](../../.gitbook/assets/examplesactions/ExampleRotateBy\_1.png)

### Logic

We then need to configure the **Logic**. This is done in the [**Logic Editor**](../../modules/logic-editor.md).

We use first a [**Get Rotation** **Node**](../incari/object/get-rotation.md), which allows us to obtain an **Object's** current `Rotation` values, and then the **RotateFromTo Action** **Node**, to which we will feed the value previously obtained and configure it for it to _rotate_ the **Object** from there to a fixed value of our choosing.

For this purpose, we set the **Attributes** of the **RotateFromTo Action** **Node** in the following way:

* `To`: $$(60, 60, 0)$$
* `Duration (sec)`: $$2$$
* `Interpolation`: `Linear`

We just leave the `From` **Attribute** as it is, since this value will be obtained through the corresponding **Input Socket**.

Then, we connect the **Object ID** from the red **Torus** [**Object Node**](../../objects-and-types/scene-objects/#objects-in-the-logic) to the `Object ID` **Input Socket** of both **Nodes**, the `Rotation` **Output** from the **Get Rotation** **Node** to the `From` **Input Socket** in the **RotateFromTo** **Node**, and a **Pulse** through the **Get Rotation** **Node** and to the `Start` **Input** in **RotateFromTo**. Thus, having the following **Logic** configuration:

![Logic configuration.](../../.gitbook/assets/examplesactions/ExampleRotateFromTo\_2.png)

### Final result

Finally, the effect of the **RotateFromTo Action** **Node** when triggered is the following:

![Final result.](../../.gitbook/assets/examplesactions/ExampleRotateFromTo\_3.gif)

## See Also

* [**RotateTo Action**](rotatetoaction.md)
* [**RotateBy Action**](rotatebyaction.md)

## External Links

* [_Rotation_](https://en.wikipedia.org/wiki/Rotation) on Wikipedia
* [_Euler angles_](https://en.wikipedia.org/wiki/Euler\_angles) on Wikipedia
