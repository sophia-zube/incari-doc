# Toggle

The **Toggle** **Object** is a **2D GUI Object** that has two states: checked or unchecked. Its initial state and colors can be customized in the [**Attributes**](toggle.md#attributes).

![Toggle.](../../../.gitbook/assets/2dgui-toggle.png)

![Toggle example.](../../../.gitbook/assets/toggle-example.gif) 

## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](toggle.md#transformation)
* [**Toggle**](toggle.md#toggle)
* [**Code**](toggle.md#code)
* [**Tag**](toggle.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/toggleattstransformation.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

### Toggle

![Toggle Attributes.](../../../.gitbook/assets/toggleattstoggle.png)

The `Toggle` **Attributes** provide crucial data for a **Toggle Object**.

* `Is checked` can be enabled or disabled. Enabled toggles it on and disabled toggles it off. 

* `Handle Color` is the color of the **Toggle's** handle. It is the small circle which appears on the background of the **Toggle**. 

* `Background Color Checked` is the color of the background when `Is checked` is enabled. 

* `Background Color Unchecked` is the color of the background when `Is checked` is disabled. 

### Code

![Code Attributes.](../../../.gitbook/assets/buttonattscode.png)

The `Code` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).

* `Class names` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.

### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Toggle**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)