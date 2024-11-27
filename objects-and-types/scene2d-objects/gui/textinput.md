# Text Input

The **Text Input** **Object** allows the user to add singleline text with a background to their **Project**. It can be completely customized in the [**Attributes**](textinput.md#attributes).

![Text Input.](../../../.gitbook/assets/textinputexample.png)

## Attributes


The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](textinput.md#transformation)
* [**Text Input**](textinput.md#text-input)
* [**Text**](textinput.md#text)
* [**Font**](textinput.md#font)
* [**Style**](textinput.md#style)
* [**Tag**](textinput.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/textinputimage220232.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

### Text Input

![Text Input Attributes.](../../../.gitbook/assets/textinputtextinputatts20232.png)

The `Text Input` **Attributes** provide crucial data for a **Text Input Object**.

* `Text` is simply the desired text.

### Text 

![Text Attributes.](../../../.gitbook/assets/textinputtextatts20232.png)

The **Text Attributes** offer the user options to customize the **Text**:

* `Color` decides the color of the text.

### Font

![Font Attributes.](../../../.gitbook/assets/textinputfontatts20232.png)

The **Font Attributes** offer the user options to customize the **Text Input's** font. Please note that while **Text Inputs** are capable of handling [*variable fonts*](../../../modules/project-settings/fonts.md#variable-fonts), only the default style will be used, as the configurable **Attributes** are not available for this **Object**.

* `Family` offers three different font types: `Manrope` and `Source Code Pro`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).

* `Size` determines the size of the font in pixels.

### Style

![Style Attributes.](../../../.gitbook/assets/textinputstyleatts20232.png)

The **Style Attributes** offer the user options to customize further visual aspects of the **Text Input**:

* The `Background Color` is the color of the **Text Input** box which appears behind the text.

* `CSS Classes` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).


### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Text Input**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)
