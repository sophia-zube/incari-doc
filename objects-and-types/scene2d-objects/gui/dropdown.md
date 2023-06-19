# Dropdown

The **Dropdown** is a **GUI** **2D Object** that allows the user to create a *dropdown menu*. The options in the menu, together with the colors and size, can be customized in the **Attributes**.

The following is a simple example of a **Dropdown** with three options:

![Dropdown.](../../../.gitbook/assets/gui-dropdown1.png)

The `Options` **Attribute** defines the options in the **Dropdown**:

![Options Attributes.](../../../.gitbook/assets/gui-dropdown-options.png)

Finally, this **Dropdown** looks like this when the **Project** is run:

![Dropdown example.](../../../.gitbook/assets/dropdown-example.gif)

## Attributes

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/dropdownattstransformation.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation.md).

### Text

![Text Attributes.](../../../.gitbook/assets/dropdownattstext.png)

There are several **Attributes** here which help customize the textual elements of a **Dropdown**. 

`Font family` offers three different font types: `monospace`, `sans-serif`, and `serif`.

`Transform` can easily change certain text aesthetics without requiring the user to change the `Text` **Attribute** itself. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase.  

`Font size (px)` determines the size of the font in pixels.

`Line height (%)` determines the placement of the text within the **Dropdown**. 

`Font color` decides the color of the **Dropdown's** text.

### Dropdown

![Dropdown Attributes.](../../../.gitbook/assets/dropdownattsdropdown.png)

`Active index` determines which `Option` is shown at the front of the **Dropdown**. Remember that the first element has the index of 0. 

`Background Color`decides the color of the **Dropdown's** background.

`Options` provides the elements which will populate the **Dropdown**. Here there are three elements called `one`, `two`, and `three`. 

Because the `Active index` is set to 1, 'two' would be element shown at the front of the **Dropdown**. 

### Code

![Code Attributes.](../../../.gitbook/assets/buttonattscode.png)

`Class names` contain the *CSS* class names of the **Object**. 

`Stylesheet` contains the *CSS* stylesheet of the **Object**.

### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Dropdown**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)