# Local Transformations

## Overview

**Local** **Transformations** are performed along the *principal axes* of an **Object**, which can be thought as the most natural axes for the rotation of an **Object**.

As an example, the **Local** axes for a cube, a cilinder, and a dome are:

![Local Axes for a cube, cilinder, and dome.](../../../../.gitbook/assets/Local_PpalAxes.gif)

**Local** **Transformations** are done directly in the **Scene Viewport** in **Local** mode. To switch to **Local** view simply click on the `Local Global` icon on the top Menu of the **Viewport**.

![Local mode view.](../../../../.gitbook/assets/TransformLocalMode_1.png)

The **Local** mode allows to change the [`Position`](#position) and [`Rotation`](#rotation) of an **Object**. It can also be used for [several **Objects**](#several-objects) and [**Groups**](#groups).

## Position

To modify an **Object's** **Position**, click on the `Translate` icon, second from left to right on the top Menu. This will show the axes along which the **Object's** **Position** can be modified. In **Local** mode, the **Object's** **Local** axes are shown.

To move an **Object** along an axis, click on the preferred axis and drag the **Object**. It can also be moved in any direction by dragging the origin of the shown axes.

The example below shows an **Object** being moved along its **Local** axes.

![](../../../../.gitbook/assets/Local_Position.gif)

## Rotation

To be able to rotate an **Object**, click on the `Rotate` icon, third from left to right on the top Menu. This will make appear the *rotation gizmo* for the **Object**. Each circle represents an axis along which a rotation can be performed. For rotating the **Object**, click on a circle of the gizmo and drag towards the direction in which to perform the rotation. In **Local** mode, the **Object** is rotated with respect to its own **Local** axes.

The example below shows an **Object** being rotated with respect to its own **Local** axes. Note that as the **Object** is rotated, its **Local** axes also rotate.

![](../../../../.gitbook/assets/Local_Rotation.gif)


## Several Objects

It is also possible to perform **Local** **Transformations** on several **Objects** at once. For this, simply select the **Objects** to modify either in the **Scene View** or in the **Scene Outliner**. It will show the *gizmo* positioned in the center of all the selected **Objects** and the axes direction of the last selected **Object**.

**Transformations** will then apply to all selected **Objects**.

The first example shows first the **Transformation** gizmo of each individual **Object** and then how it looks when they are all selected.

![](../../../../.gitbook/assets/LocalGlobal_SeveralObj1.gif)

The next two examples show the translation of two cubes and the rotation of two cilinders, respectively.

![](../../../../.gitbook/assets/LocalGlobal_SeveralObj2.gif)

![](../../../../.gitbook/assets/LocalGlobal_SeveralObj3.gif)




## Groups

Another way of performing **Transformations** over several **Objects** is by putting them into a **Group**. Then, performing **Transformations** over the **Group** will **Transform** the **Objects** that compose it as if they all were just parts of only one **Object**.

The example below shows a **Local** rotations and translation of a **Group** composed of two cilinders and a cube.

![](../../../../.gitbook/assets/Local_Group.gif)


## External Links

* [*Principal Axes*](https://en.wikipedia.org/wiki/Moment_of_inertia#Principal_axes) on Wikipedia.
