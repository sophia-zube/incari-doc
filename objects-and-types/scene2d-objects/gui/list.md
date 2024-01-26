# List

A **List** is a **GUI 2D Object** that allows the user to create a *list*. The contents of the list, and any visual components, can be customized in the [**Attributes**](list.md#attributes).  

## Attributes

The **Object's** **Attributes** can be used to fully customize the **Object**. Explained below, they are:

* [**Transformation**](list.md#transformation)
* [**List**](list.md#list)
* [**List Item**](list.md#list-item)
* [**Separator**](list.md#separator)
* [**Text**](list.md#text)
* [**Font**](list.md#font)
* [**Style**](list.md#style)
* [**Tag**](list.md#tag)

### Transformation

![Transformation Attributes.](../../../.gitbook/assets/listtransformationatts.png)

The `Transformation` **Attributes** deal with placement, rotation, and size in *XY* space. More information can be found [here](../../attributes/common-attributes/transformation/README.md).


### List

The `List` **Attributes** provide crucial data for a **List Object**. When `Advanced Mode` is toggled on, the **Attribtues** differ slightly. 

![List Attributes: Advanced Mode Off.](../../../.gitbook/assets/list2dsimple.png)

![List Attributes: Advanced Mode On.](../../../.gitbook/assets/list2dadvanced.png)

* The `Active Index` **Attribute** decides which item is currently active in the **List**.

* `Advanced Mode` determines whether `Entries` or `JSON File` will appear in the **Attributes**.

* `Entries` allows the user to add the elements of the **List** and is only visible when `Advanced Mode` is toggled off.
* The `JSON File` contains all the information for the **List** when `Advanced Mode` is toggled on. 

Thus there are two ways to populate a **List**: 

* When `Advanced Mode` is toggled on, the `JSON File` **Attribute** appears. The `JSON File` contains more specific data of the **List** and allows the user to have more control. For example, a *JSON* file could contain something like this:


```
   [
    {
        "icon": "Users/user.name/Documents/Project1/Assets/image1.jpg",
        "text": "you collected"
    },
    {
        "icon": "Users/user.name/Documents/Project1/Assets/image2.png",
        "text": "over 9000"
    },
    {
        "icon": "Users/user.name/Documents/Project1/Assets/image3.png",
        "text": "overhours"
    }
]
```

* When `Advanced Mode` is toggled off, the `Entries` are visible. The user can manually input each **List** entry one by one. 
  
  ![Example List Entries with Icons.](../../../.gitbook/assets/listimage420232.png)


These two processes result in a **List** that appears like this (with some other visual **Attributes** changed):

![](../../../.gitbook/assets/listexample2.png)


### List Item

![List Item Attributes.](../../../.gitbook/assets/listlistitemnew.png)

The `List Item` **Attributes** provide crucial data for a **List Object's** items.

* `Height` decides the space between each segment of the list (the total vertical space of an item) in pixels.
* `Background Color` decides the background color of the **List's** items.
* `Use Icon` toggles the visibility of any icons in the **JSON** file on or off. Please note, for icon images the absolute path on one's local machine must be used. 
* `Icon Size` determines the size of the icons in pixels.


### Separator

![Separator Attributes.](../../../.gitbook/assets/listitemseparator.png)

* `Size` chooses the thickness of the separators, which are the lines between **List** items, in pixels. 
* `Color` determines the color of the separators. 

### Text

![Text Attributes.](../../../.gitbook/assets/listtextnew.png)

The `Text` **Attributes** customize the textual elements of a **List**. 

<!--* `Font family` offers three different font types: `monospace`, `sans-serif`, and `serif`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).-->

* `Color` decides the color of the **List's** text.
* `Alignment` sets the alignment of the text. This is either left, right, or center.

* `Transform` can easily change certain text aesthetics. `Capitalize` makes the first letter capital, `uppercase` makes all letters capital, and `lowercase` makes all letters lowercase.  

<!--* `Font size (px)` determines the size of the font in pixels.-->

 
### Font 

![Font Attributes.](../../../.gitbook/assets/listfontatts.png)


The `Font` Attributes control certain font characteristics. 

* `Family` offers three different font types: `monospace`, `sans-serif`, and `serif`. More fonts can be added by the user in [**Project Settings**](../../../modules/project-settings/fonts.md).

* `Size` determines the size of the font in pixels.

### Style 

![Style Attributes.](../../../.gitbook/assets/liststyleatts.png)

* The `Text Margin` **Attribute** adds *margins* to the text of a **List** depending on what sizes are specified and for which sides. The options are `x` for the top, `y` for the right, `z` for the bottom, and `w` for the left. [Margins](https://www.w3schools.com/Css/css_margin.asp) are often seen in the context of *CSS*. Similarly, here, it is the extra space around the **List** item's text in relation to the space around it.  
* `List Padding` adds *padding* to a **List** depending on what sizes are specified and for which sides. The options are `x` for the top, `y` for the right, `z` for the bottom, and `w` for the left. [Padding](https://www.w3schools.com/cssref/pr_padding.php) is often seen in the context of *CSS*. Similarly, in **Incari**, it is the extra space inside the **List Object** itself. The separators of the **List** do not extend into this space. 
* `List Margin` adds *margins* to a **List** depending on what sizes are specified and for which sides. The options are `x` for the top, `y` for the right, `z` for the bottom, and `w` for the left. [Margins](https://www.w3schools.com/Css/css_margin.asp) are often seen in the context of *CSS*. Similarly, here, it is the extra space around the **List** in relation to other **Objects**. 
* `Icon Margin` adds *margins* to the icons of a **List's** depending on what sizes are specified and for which sides. The options are `x` for the top, `y` for the right, `z` for the bottom, and `w` for the left. [Margins](https://www.w3schools.com/Css/css_margin.asp) are often seen in the context of *CSS*. Similarly, here, it is the extra space around the **List** item's icon in relation to the space around it.
* `CSS Classes` contains the *CSS* class names of the **Object**.
* `Stylesheet` contains the *CSS* stylesheet of the **Object**. 


### Tag

![Tag Attributes.](../../../.gitbook/assets/buttonattstag.png)

This **Attribute** manages the *tags* for the **List**. See more on *tags* [here.](../../attributes/common-attributes/tag.md)








<!--### Text

![Text Attributes.](../../../.gitbook/assets/listtext2atts.png)



### List Item Icon

![List Item Icon Attributes.](../../../.gitbook/assets/listlistitemiconatts.png)

The `List Item Icon` **Attributes** provide crucial data for a **List Object's** icons.
 

* `Icon Background` decides the background color of the icons.



### Data

![List Data Attributes.](../../../.gitbook/assets/listdatatts.png)



### Code

![Code Attributes.](../../../.gitbook/assets/buttonattscode.png)

The `Code` **Attributes** allow for more customizability. This can override any stylesheet provided in the [**Project Settings**](../../../modules/project-settings/style.md) or a [**Scene2D**](../../project-objects/scene2d.md). 

To address these in the **Logic**, please refer to the [**Object 2D Nodes**](../../../toolbox/incari/object2d/README.md).

* `Class names` contain the *CSS* class names of the **Object**. 

* `Stylesheet` contains the *CSS* stylesheet of the **Object**.-->

