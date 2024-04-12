# Scene

![](../../.gitbook/assets/scene20232.png)

A **Scene** is a collection of **Objects** that represent different unique places within your *User Interface*, such as menus, maps, and media players. Each **Scene** has its own _3D_ space. The **Size** of each _3D_ space are determined by the **Attributes** of the **Screen** that it is assigned to.

## Camera

`Player Camera`: Determines the **Camera** that will show the **Scene** when the **Scene** starts. See [**Camera**](../scene-objects/camera.md) for more info on **Camera Objects**.

## Environment Lighting

This **Attribute** defines the background of the **Simulation** when `Scene Environment` is selected in the [**Screen's** `Background`](screen.md#background). 

There are two `Lighting types` the user can choose from: `Color` and `Environment Map`. 

When `Color` is selected, further **Attributes** allow the user to choose the `Color` (or provide the hexadecimal code) of the `Environment Lighting` and its `Brightness`. 

![](../../.gitbook/assets/sceneenvlightinggif1.gif)

When `Scene Environment` is selected, several **Attributes** appear.

`Environment Map` allows the user to add a file of an *Environment Map*. This can then be manipulated with `Tint`, `Exposure`, `Rotation`, `Tilt`, and `Projection Height` to produce the desired effect. 

![](../../.gitbook/assets/sceneenvlightinggif2.gif)



<!-- There are a few **Nodes**, such as the [**KeyPress** **Node**](../../toolbox/events/keyboard/on-key-press.md), which require a **Scene Object** to be assigned as an **Attribute**. This can be done by dragging and dropping a **Scene** from the **Project Outliner** into the **Scene Attribute** of that **Node**. -->

