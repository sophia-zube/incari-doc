# Text Area

The **Text Area** **Object** allows the user to add multiline text with a background to their **Project**. It can be completely customized in the [**Attributes**](textarea.md#attributes).

![Text Area.](../../../.gitbook/assets/2dgui-textarea1.png)


## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](textarea.md#transformation)
* [**Text**](textarea.md#text)
* [**Text Area**](textarea.md#text-area)
* [**Code**](textarea.md#code)
* [**Tag**](textarea.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/textareaattstransformation.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

### Text

![Text Attributes.](../../../.gitbook/assets/textareaattstext.png)
 
The **Text Attributes** offer the user options to customize the **Text**:

* `Font family` offers three different font types: `monospace`, `sans-serif`, and `serif`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).

* `Font size (px)` determines the size of the font in pixels.

* `Line height (%)` determines the placement of the text within the text box. 

* `Font color` decides the color of the text.

### Text Area

![Text Area Attributes.](../../../.gitbook/assets/textareaattstextarea.png)

The `Text Area` **Attributes** provide crucial data for a **Text Area Object**.

* `Text Area` is simply the desired text.

* `Word Wrap` can be enabled and disabled. When it is enabled, the text fits within the confines of the **Text Area**. If disabled, the text will be in one line and may run off the **Text Area**, causing some text to not be visible. In this case, please adjust the dimensions of the **Text Area**.

* The `Background Color` is the color of the **Text Area** box which appears behind the text. 

### Code

![Code Attributes.](../../../.gitbook/assets/buttonattscode.png)

The `Code` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).

* `Class names` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.


### Tag 

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Text Area**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)
