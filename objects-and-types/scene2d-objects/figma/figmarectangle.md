# Rectangle

The **Rectangle** in **Incari** provides similar functionality as its equivalent in *Figma*. 

![Rectangle.](../../../.gitbook/assets/rectangle2dimage120232.png)

There are several **Attributes** which allow the user heightened customizability and control. 

* [**Transformation**](figmarectangle.md#transformation)
* [**Blending**](figmarectangle.md#blending)
* [**Fill**](figmarectangle.md#fill)
* [**Stroke**](figmarectangle.md#stroke)
* [**Effects**](figmarectangle.md#effects)
* [**Mask**](figmarectangle.md#mask)
* [**Style**](figmarectangle.md#style)
* [**Tag**](figmarectangle.md#tag)


# Attributes

## Transformation

![Transformation Attributes.](../../../.gitbook/assets/buttonattstransformation.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

## Blending

![Blending Attributes.](../../../.gitbook/assets/figmablendingattribute.png)

This **Attribute** lets the user set a `Blend Mode` as a base property of the **Rectangle**. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). An **Object's** `Blend Mode` can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

## Fill

The `Fill` **Attributes** consist of different items called `Elements`. Each `Element` contains a `Type`. This can be either `Solid` or `Image` and changes some of the available **Attributes** under this category.

If there is more than one `Fill Element`, the most recent one will take precedent over the others (unless some `Blend Mode` is applied).

### Solid

![Fill Attributes with Type Solid.](../../../.gitbook/assets/booleanoperationfill20232.png)

When `Solid` is selected, `Color` is visible. 

* `Color` is a color selector that lets the user pick the `Fill's` color. 

* Similar to the base property described previously, `Blend Mode` here affects the `Fill Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Fill` appears. This is represented by an integer between 0 and 1.

### Gradient

![Fill Attributes with Type Gradient.](../../../.gitbook/assets/fillattributesgradient.png)

When `Gradient` is selected, `Gradient` is visible. 

* `Gradient` decides the style of gradient, which can be either `Linear`, `Radial`, `Angular`, or `Diamond`.
  
* The `Gradient` color selector has a row of squares going left to right as well as a column going top to bottom. These correspond 1:1 with each other, so in the image above the mustard yellow squares are the same color. The user can drag the squares in the row to change the order of the gradient's colors. Clicking anywhere in the bar will add a square in both the row and column of colors. The user can change the color of a square by clicking it, which opens the color picker. 

* Similar to the base property described previously, `Blend Mode` here affects the `Fill Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Fill` appears. This is represented by an integer between 0 and 1.

### Image

![Fill Attributes with Type Image.](../../../.gitbook/assets/figmafillimageatts.png) 

When `Image` is selected, `Image` and `Fit Mode` are visible. 

* `Image` is the desired **Texture** file.
  
* `Fit Mode` determines how the **Texture** is displayed. These can be `Fill`, `Fit`, `Crop`, and `Tile`. `Tile` has the additional **Attribute** of `Scale Factor`, which augments the tesselation. 

* Similar to the base property described previously, `Blend Mode` here affects the `Fill Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Fill` appears. This is represented by an integer between 0 and 1.

### Video

![Fill Attributes with Type Video.](../../../.gitbook/assets/fillattributesvideo.png) 

When `Image` is selected, `Video` and `Fit Mode` are visible. 

* `Video` is the desired **Video** file.
  
* `Fit Mode` determines how the **Video** is displayed. These can be `Fill`, `Fit`, `Crop`, and `Tile`. `Tile` has the additional **Attribute** of `Scale Factor`, which augments the tesselation.
   
* Below `Fit Mode` are three options: `Play`, `Pause`, and `Stop`. `Play` starts the video in the **Scene2D**, `Pause` halts it at the frame it is currently on, and `Stop` halts it and reset it to the beginning. 

* `Loop` is a *Bool* that when toggled on, makes the video repeat itself once it finishes. This is continous. 

* Similar to the base property described previously, `Blend Mode` here affects the `Fill Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Fill` appears. This is represented by an integer between 0 and 1.

## Stroke

The `Stroke` **Attributes** consist of different items called `Elements`. Each `Element` contains a `Type`. This can be either `Solid` or `Image` and changes some of the available **Attributes** under this category. There are also two fixed **Attributes** outside of the `Elements`. These are:

* `Width`, which is how wide (in pixels) each `Stroke` will appear. This applies to each `Stroke Element`. 
* `Position`, which determines what part of the outline identifies the outside of the **Object**. For example, if `Inner` is selected, then the outside of the `Stroke` is the outside of the **Object**. If `Center` is selected, then the `Stroke's` center is the outside of the **Object**. If `Outer` is selected, then the inside of the `Stroke` is the outside of the **Object**.

### Solid

![Stroke Attributes with Type Solid.](../../../.gitbook/assets/booleanoperationstroke20232.png)

When `Solid` is selected, `Color` is visible. 

* `Color` is a color selector that lets the user pick the `Stroke's` color. 

* Similar to the base property described previously, `Blend Mode` here affects the `Stroke Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Stroke` appears. This is represented by an integer between 0 and 1.

Please note that when a new `Fill` is added, it is added to the top of the *fill* list and the **Object** will be updated to display this `Fill`.

### Gradient

![Stroke Attributes with Type Gradient.](../../../.gitbook/assets/strokeattributegradient.png)

When `Gradient` is selected, `Gradient` is visible. 

* `Gradient` decides the style of gradient, which can be either `Linear`, `Radial`, `Angular`, or `Diamond`.
  
* The `Gradient` color selector has a row of squares going left to right as well as a column going top to bottom. These correspond 1:1 with each other, so in the image above the mustard yellow squares are the same color. The user can drag the squares in the row to change the order of the gradient's colors. Clicking anywhere in the bar will add a square in both the row and column of colors. The user can change the color of a square by clicking it, which opens the color picker. 

* Similar to the base property described previously, `Blend Mode` here affects the `Stroke Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Stroke` appears. This is represented by an integer between 0 and 1.


### Image

![Stroke Attributes with Type Image.](../../../.gitbook/assets/figmastrokeimage.png)

When `Image` is selected, `Image` and `Fit Mode` are visible. 

* `Image` is the desired **Texture** file.
  
* `Fit Mode` determines how the **Texture** is displayed. These can be `Fill`, `Fit`, `Crop`, and `Tile`. `Tile` has the additional **Attribute** of `Scale Factor`, which augments the tesselation. 

* Similar to the base property described previously, `Blend Mode` here affects the `Stroke Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Fill` appears. This is represented by an integer between 0 and 1.

### Video

![Stroke Attributes with Type Video.](../../../.gitbook/assets/strokeattributesvideo.png) 

When `Image` is selected, `Video` and `Fit Mode` are visible. 

* `Video` is the desired **Video** file.
  
* `Fit Mode` determines how the **Video** is displayed. These can be `Fill`, `Fit`, `Crop`, and `Tile`. `Tile` has the additional **Attribute** of `Scale Factor`, which augments the tesselation.
   
* Below `Fit Mode` are three options: `Play`, `Pause`, and `Stop`. `Play` starts the video in the **Scene2D**, `Pause` halts it at the frame it is currently on, and `Stop` halts it and reset it to the beginning. 

* `Loop` is a *Bool* that when toggled on, makes the video repeat itself once it finishes. This is continous. 

* Similar to the base property described previously, `Blend Mode` here affects the `Stroke Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).

* `Opacity` refers to how opaque or transparent the `Stroke` appears. This is represented by an integer between 0 and 1.


## Effects

The `Effects` **Attribute** consists of different items called `Elements`. Each `Element` contains a `Type`. These are `Drop Shadow`, `Inner Shadow`, `Layer Blur`, and `Background Blur`. The available **Attributes** are described below:

### Drop Shadow and Inner Shadow

![Effect Attributes with Drop Shadow Selected.](../../../.gitbook/assets/figmaeffectsatts.png)

There are two *shadow* `Types`. `Drop Shadow` adds a *shadow* behind the **Object**. `Inner Shadow` adds a *shadow* within the **Object**.

![Rectangle with a Drop Shadow.](../../../.gitbook/assets/rectangledropshadow.png)

![Rectangle with an Inner Shadow.](../../../.gitbook/assets/rectangleinnershadow.png)

* `Offset` sets the location of the *shadow* in relation to the **Object**. 

* `Blur` modifies the softness of the shadow. When there is no blur, the shadow appears completely solid with rigid lines. When blur is applied, the shadow becomes transfused.  

* `Spread` inflates or deflates the shadowshape on which the blur is applied.

* `Color` changes the color of the shadow.

* `Blend Mode` affects the `Effects Elements` only. These are established on common formulas, examples of each can be accessed [here](http://www.simplefilter.de/en/basics/mixmods.html). It can also be set with the [**Set Blend Mode Node**](../../../toolbox/incari/object2d/setblendmode.md).


### Layer Blur and Background Blur 

![Effects Attributes with Layer Blur Selected.](../../../.gitbook/assets/figmaeffectsattsblur.png)

There are two *blur* `Types`. `Layer Blur` blurs the **Object** itself and `Background Blur` applies a blur to whatever is directly behind the **Object**. This latter blur type is better seen when the **Object's** opacity or `Fill` opacity has been reduced. 

![Rectangle with a Layer Blur.](../../../.gitbook/assets/rectanglelayerblurreal.png)

![Rectangle with a Background Blur.](../../../.gitbook/assets/rectanglebackgroundblur.png)

* `Blur` increases the severity of the blur effect. 

## Mask 

A **Mask** is an **Object** that shows a certain area of another **Object** while concealing the rest. Any **Object** (e.g., an **Ellipse**, **Rectangle**, **Frame**, **Group**, or **Text**) can be used as a **Mask**. 

For easier visualization, think of the **Mask** as a cookie cutter while the masked **Object** is the dough: the cookie cutter shows only a part and discards the rest.

![Mask Attributes.](../../../.gitbook/assets/figmamaskattsreal.png)

The `Type` **Attribute** has three options:

* `None` - nothing is applied. 
* `Alpha` - the **Mask** has an opacity level (alpha channel) determining with which level of opacity (or transparency) the masked **Object** is revealed: 0% opacity reveals nothing, 100% opacity is equivalent to a **Mask** with `Vector` type.
* `Vector` - only modifies the shape outline of the masked **Object**
* `Luminance` - allows the user to utilize brightness to determine the effect of the **Mask**; the brighter the area of a **Mask**, the more that is revealed and the darker the area, the less that is revealed.

`Object` allows the user to select what should be the masked **Object**.

`Apply Mask` is a toggle that applies the **Mask** when set to on, and disables the **Mask** when set to off. 

## Style 

![Style Attributes.](../../../.gitbook/assets/rectanglestyleatts.png)

This **Attribute** gives the user purview over how round the **Rectangle's** corners are, specifiying the size of the radius for the curve. 

## Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Button**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)