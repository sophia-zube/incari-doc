# Sprite

## Overview

A **Sprite** places a graphic **Asset** onto a two-dimensional plane in the **Scene**. 

Like any other **Scene Object**, we can manipulate the **Position**, **Rotation** and **Scale** of a **Sprite** using the **Transformation Attributes** and adjusting its **Rotation Pivot**.

## Effects

### Tint

The `Tint` **Attribute** applies a *color overlay* to the **Sprite Object**, thereby changing its appearance. The *color overlay* can be set by manually adjusting the the **HSB** / **RGBA** values or inserting a **Hex Code**, using their corresponding [**Color Attribute**](../attributes/attribute-types/color-attributes.md).

## Mask

### Use Mask

**Mask**s obscure or reveal parts of a **Sprite Object** that it's applied to. If the *toggle* is activated, the **Mask** supplied to the `Object` **Attribute** would be applied to the **Sprite Object**.

### Object

![](../../../.gitbook/assets/objects/scene-objects/sprites/sprite/mask.PNG)

A **Mask** can be added to a **Sprite Object** by clicking the **Assert** slot and selecting it from the drop-down **Scene Outliner**.

### Invert Mask
`Invert Mask` turns a **Mask** upside down When it is activated.

## Sprite 
## Size

`Size` determines the dimensions of a graphic. As **Sprite Objects** are two-dimensional, the `Z` **Value** doesn't have any effect.

If you want to display the graphic with the precise _pixel_ resolution, you should ensure that `Size` matches the **Asset**'s pixel dimensions, and that the **Object**'s `Position` is placed on the same plane as the **Scene**'s **Camera**.

The graphic's dimensions will be loaded correctly when you create a new **Sprite** **Object**, by dragging a graphic from the **Asset Manager**.

## Alpha

`Alpha` determines the opacity of a **Sprite** with 0 being completely transparent and 1 being completely opaque.

![](../../../.gitbook/assets/sprite-alpha.gif)

## Flip U / Flip V

The horizontal and vertical coordinates in most 2D graphics programs are referred to as _XY_ coordinates. In 3D applications, though, it is conventional to call these _UV_ coordinates to differentiate between 3D _mesh_ transformation coordinates and 2D _texture_ transformation coordinates.

The `Flip U` and `Flip V` **Attributes** simply inverts the direction of the corresponding axis, meaning that `Flip U` flips a **Sprite** _horizontally_, while `Flip V` will flip it _vertically_.

![](../../../.gitbook/assets/sprite-uv.gif)

## Sort Index

Because Incari works in 3D, it has no way of automatically discerning which elements should be shown on top of which, when they occupy the same area in 3D space. It is therefore, necessary to manually define the _sort order_ of **Sprites** to ensure that they are layered correctly.

This is done by manipulating the `Sort Index` **Sprites** with higher values being rendered above lower values. If **Sprites** have the same `Sort Index` **Value**, then there is no guarantee that they will be shown correctly, and therefore it is recommended that you assign a unique **Value** to each **Sprite** unless you are certain that they will never overlap one another.

![](../../../.gitbook/assets/sprite-sort-index.gif)

## Diffuse Texture

![](../../../.gitbook/assets/objects/scene-objects/sprites/sprite/diffuse.PNG)

The `Diffuse Texture` **Attribute** contains a reference to a graphic **Assert** that is loaded in a **Scene** and this **Assert** can be found in the **Asset Manager**. The **Attribute** is assigned by default if you drag and drop the **Assert** into the **Scene**.

Also, the **Assert** can be dragged and dropped from the **Assert Manager** into the **Attribute** slot.

## Use Opacity Map

Opacity maps are gray-scale graphics that allows **Sprite Objects** to have a transparent detail. Black pixels show areas as completely transparent while white pixels show them as opaque, with variations in gray showing different levels of transparency.

Opacity map **Assert** supplied to the `Opacity Map` **Attribute** are used if this toggle is activated.

## Opacity Map

![](../../../.gitbook/assets/objects/scene-objects/sprites/sprite/diffuse.PNG)

An Opacity map can be added to this **Attribute** by clicking the **Assert** slot and selecting it from drop-down **Assert Manager**.

Also, the **Assert** can be dragged and dropped from the **Assert Manager** into the **Attribute** slot.