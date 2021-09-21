# Animation Editor

## Overview

The **Animation Editor** is used for creating and editing key-frame based timeline animation, which have the file extension .incani. It can either be opened from the `View` drop-down menu on the top panel of **Incari** or by double-clicking an animation **Asset** in the **Asset Manager**.

![](../.gitbook/assets/animation-editor2.png)

## Animation Editor Window

![](../.gitbook/assets/animation-editor3.png)

**Animation Editor** - The main window, which contains all the option to create and edit an animation. The specifics of its sections are described below.

## Toolbar

![](../.gitbook/assets/animation-editor-top-panel.png)

The **Toolbar** offers several options to modify an animation, such as adding or deleting an animation block, adding or deleting a keyframe, and modifying the type of interpolation used. It also gives options for a better visualization of the timeline, such as a focus on just the visible lines and a toggle for the visibility of the tangent lines. The rest of the options are for enabling the preview and playing and controlling the animation.

## Left Panel

![](../.gitbook/assets/animation-editor-left-panel-2.png)

The **Left Panel** shows the **Animation Blocks** with their **Transformation Attributes** and corresponding **Keyframes**, which are highlighted in blue.

A **Keyframe** consists of two parts:

* The **Keyframe** itself, which holds a value at a specific time.
* The curve handles, which control the easing and interpolation between frames.

To add a **Keyframe**, simply right click an Attribute and select `Add Keyframe` from the context menu. This will create a **Keyframe** at whatever time the playhead is currently on. The curve handles can then be adjusted to fine-tune the intermediate frames.

When a **Keyframe** is selected, its corresponding Bézier curve is shown in the **Animation Timeline**.

When the animation is run, the **Left Panel** shows the evolving values of the **Transformation Attributes**.

![](../.gitbook/assets/anim-editor-run.gif)

## Animation Timeline

![](../.gitbook/assets/animation-editor-central.png)

The **Animation Timeline** shows a graph with the Bézier curves of the **Transformation Attributes**.

## See Also

* [**4 Methods of Animation - 1. Animation Editor**](../demo-projects/4-methods-of-animation.md#1-animation-editor)

## External Link

* [_Bézier Curve_](https://en.wikipedia.org/wiki/B%C3%A9zier_curve) on Wikipedia.

