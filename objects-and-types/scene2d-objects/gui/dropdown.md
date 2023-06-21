# Dropdown

The **Dropdown** is a **GUI** **2D Object** that allows the user to create a *dropdown menu*. The options in the menu, together with the colors and size, can be customized in the [**Attributes**](dropdown.md#attributes).

![Dropdown GUI Object.](../../../.gitbook/assets/dropdownexampleimage.png)


## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](dropdown.md#transformation)
* [**Text**](dropdown.md#text)
* [**Dropdown**](dropdown.md#dropdown)
* [**Code**](dropdown.md#code)
* [**Tag**](dropdown.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/dropdownattstransformation.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).

### Text

![Text Attributes.](../../../.gitbook/assets/dropdownattstext.png)

The `Text` **Attributes** customize the textual elements of a **Dropdown**. 

* `Font family` offers three different font types: `monospace`, `sans-serif`, and `serif`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md)

* `Transform` can easily change certain text aesthetics without requiring the user to change the `Options` **Attributes** themselves. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase.  

* `Font size (px)` determines the size of the font in pixels.

* `Line height (%)` determines the placement of the text within the **Dropdown**. 

* `Font color` decides the color of the **Dropdown's** text.

### Dropdown

![Dropdown Attributes.](../../../.gitbook/assets/dropdownattsdropdown.png)

The `Dropdown` **Attributes** provide crucial data for a **Dropdown Object**.

* `Active index` determines which `Option` is shown at the front of the **Dropdown**. Remember that the first element has the index of 0. 

* `Background Color`decides the color of the **Dropdown's** background.

* `Options` provides the elements which will populate the **Dropdown**. Here there are three elements called `one`, `two`, and `three`. 

In the above image, because the `Active index` is set to 1, 'two' would be element shown at the front of the **Dropdown**. 

### Code

![Code Attributes.](../../../.gitbook/assets/buttonattscode.png)

The `Code` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md)

* `Class names` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.

### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Dropdown**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)

## Example

The following is a simple example of a **Dropdown** with three options:

![Dropdown.](../../../.gitbook/assets/gui-dropdown1.png)

The `Options` **Attribute** defines the options in the **Dropdown**:

![Options Attributes.](../../../.gitbook/assets/gui-dropdown-options.png)

Finally, this **Dropdown** looks like this when the **Project** is run:

![Dropdown example.](../../../.gitbook/assets/dropdown-example.gif)