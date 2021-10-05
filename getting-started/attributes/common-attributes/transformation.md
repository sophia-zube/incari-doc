# Transformation

All **Objects** in **Incari** exist in _3D_ space, and have a set of **Attributes** to define their **Transformation** data. **Transformation** is divided into three **Vector3** type **Attributes**: `Position`, `Rotation` and `Scale`.

## Position

`Position` is defined by three values, representing each of the three axes of a three dimensional Cartesian coordinate system.

In most _2D_ graphics applications, you will typically see a coordinate system with the origin \(0,0\) at the top-left corner of a document, and the X value increasing from left-to-right and the Y value increasing from top-to-bottom.

In **Incari**, coordinates are in 3D Euclidean space, with the origin \(0, 0, 0\) at the center, and the `x` value increasing from centre-to-right, the `y` value increasing from center-to-top and the `z` value increasing from center-to-front.

Any point in space can be determined by these `x`, `y` and `z` values.

![](../../../.gitbook/assets/coordinates%20%281%29.png)

## Rotation

The `Rotation` **Attribute** represents the Euler angle of rotation of an **Object** along each of its axes. The **Object** is rotated in _local space_, meaning that any adjustments will be made along its _own_ axes, not the axes of the **Scene** itself. Axes can be thought of as being like three skewers, going through the **Object** and intersecting at the **Object**'s **Pivot Point**.

![](../../../.gitbook/assets/rotation.gif)

## Scale

`Scale` multiplies the size of an **Object** along its axes, relative to its **Origin**. By default, `Scale` is set to 1, 1, 1, meaning that it is at 100% of its size on all axes.

![](../../../.gitbook/assets/scale.gif)

