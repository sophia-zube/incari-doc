# Dropdown

The **Dropdown** is a **GUI** **2D Object** that allows the user to create a *dropdown menu*. The options in the menu, together with the colors and size, can be customized in the [**Attributes**](dropdown.md#attributes).

![Dropdown GUI Object.](../../../.gitbook/assets/dropdownimage120241.png)


## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](dropdown.md#transformation)
* [**Dropdown**](dropdown.md#dropdown)
* [**Text**](dropdown.md#text)
* [**Font**](dropdown.md#)
* [**Style**](dropdown.md#style)
* [**Tag**](dropdown.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/dropdowntransformation20241.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).


### Dropdown

![Dropdown Attributes.](../../../.gitbook/assets/dropdownatts20241.png)

The `Dropdown` **Attributes** provide crucial data for a **Dropdown Object**. The `Options` have two types: `Static Text` and `Translation`. This can be switched using the text or translation icons to the right, in that order. 

![Static Text and Translation.](../../../.gitbook/assets/textvstranslation.png)

* `Active index` determines which `Option` is shown at the front of the **Dropdown**. Remember that the first element has the index of 0. 

* `Options` provides the elements which will populate the **Dropdown**. Here there are three elements called `one`, `two`, and `phrase`. The first two are of type `Static Text`, where the user simply types the desired text. The third is of type `Translation`, which lets the user choose the key of the current language (which is established in the [**Project Settings**](../../../modules/project-settings/localization.md)). In the image above, the selected key is `phrase`.

In the above image, because the `Active index` is set to 0, 'one' would be element shown at the front of the **Dropdown**. 


### Text

![Text Attributes.](../../../.gitbook/assets/dropdowntext20241.png)

The `Text` **Attributes** customize the textual elements of a **Dropdown**. 

* `Color` decides the color of the **Dropdown's** text.

* `Transform` can easily change certain text aesthetics without requiring the user to change the `Options` **Attributes** themselves. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase.  

* `Line height (%)` determines the placement of the text within the **Dropdown**. 



### Font

![Font Attributes.](../../../.gitbook/assets/fontatts20241.png)

The `Font` **Attributes** focus on the details of the **Drowpdown's** text. Please note that while **Dropdowns** are capable of handling [*variable fonts*](../../../modules/project-settings/fonts.md#variable-fonts), only the default style will be used, as the configurable **Attributes** are not available for this **Object**.

* `Family` offers two different font types: `Manrope` and `Source Code Pro`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).

* `Size` determines the size of the font in pixels.


### Style

![Style Attributes.](../../../.gitbook/assets/dropdownstyleatts20241.png)

The `Style` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).

* `Background Color` decides the color of the **Dropdown's** background.
  
* `CSS Classes` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.

### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **Dropdown**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)

## Example

The following is a simple example of a **Dropdown** with three options:

![Dropdown.](../../../.gitbook/assets/dropdownimage3rdtolast20241.png)

The `Options` **Attribute** defines the options in the **Dropdown**:

![Options Attributes.](../../../.gitbook/assets/dropdown2ndtolast20241.png)

Finally, this **Dropdown** looks like this when the **Project** is run:

![Dropdown example.](../../../.gitbook/assets/dropdown-example.gif)