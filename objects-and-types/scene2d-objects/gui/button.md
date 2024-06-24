# Button

The **Button** **GUI** **Object** is a simple icon to attach **Logic** to. It can be configured so that something occurs when it is clicked in tandem with using the [**Mouse Nodes**](../../../toolbox/events/mouse/README.md). A **Button's** text, placement, and size can be altered using the [**Attributes**](button.md#attributes). 

![Button.](../../../.gitbook/assets/buttonimage120232.png)

![Button with Text.](../../../.gitbook/assets/buttonimage220232.png)


## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](button.md#transformation)
* [**Text**](button.md#text)
* [**Font**](button.md#font)
* [**Style**](button.md#code)
* [**Tag**](button.md#tag)
  
### Transformation

![Transformation Attributes.](../../../.gitbook/assets/buttonimage320232.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

### Text

![Text Attributes.](../../../.gitbook/assets/buttonattstext.png)

The `Text` **Attributes** customize the textual elements of a **Button**.

There are two ways the `Text` Attribute can be incorporated in the **Object**. That is either as `Static Text` or `Translation`. This can be switched using the text or translation icons to the right, in that order. 

![Static Text and Translation.](../../../.gitbook/assets/textvstranslation.png)

#### Static Text

![Static Text Attributes.](../../../.gitbook/assets/statictextatts20241.png)

When `Static Text` is selected, the **Attributes** are:

* `Text` is the text itself which will be displayed on the **Button**. Please note that only text which fits within the confines of the **Button** will be displayed. Size the **Button** accordingly. 

* `Color` decides the color of the **Button's** text.

* `Transform` can easily change certain text aesthetics without requiring the user to change the `Text` **Attribute** itself. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase. 

#### Translation

![Translation Attributes.](../../../.gitbook/assets/translationatts20241.png)

When `Translation` is selected, the **Attributes** are:

* `Translation` lets the user choose the key of the current language (which is established in the [**Project Settings**](../../../modules/project-settings/localization.md)). In the image above, the selected key is `phrase`.
  
* `Color` decides the color of the **Button's** translation. 

* `Transform` can easily change certain text aesthetics without requiring the user to change the `Translation` **Attribute** itself. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase. 

### Font

![Font Attributes.](../../../.gitbook/assets/fontatts20241.png)

The `Font` **Attributes** focus on the details of the **Button's** text.

* `Family` offers three different font types: `monospace`, `sans-serif`, and `serif`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).

* `Size` determines the size of the font in pixels.


### Style

![Style Attributes.](../../../.gitbook/assets/styleattsbutton20241.png)

The `Style` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).

* `Background Color` determines the color of the **Button** itself. In the example image above, it is green. 

* `Border Radius (px)` decides to what extent the corners and edges of the **Button** are rounded. 

* `CSS Classes` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.

### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Button**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)