# What's New

Many new features have been added to the release of **Incari Studio** 2023.1. Here is a list of the features you need to know.

## Custom Shading

The [**Material Editor**](../modules/material-editor/README.md) now includes a new shading model called the [**Custom Shading**](../modules/material-editor/customshadingmodel.md). It allows the user to create and customize their own shading model. This expands the possibilities for **Materials** in **Incari**. 

The customization is done via `Vertex Shader` or `Fragment Shader`. 

![Custom Shading Example.](../.gitbook/assets/customshadingmodel.gif)

## [Asset Database](../modules/asset-database.md)

A new [**Module**](../modules/overview.md) has been introduced with this release: the [**Asset Database**](../modules/asset-database.md), which is a *database* of all the **Assets** that are either used in the **Project** or available to be used at runtime. It allows the user to keep track of all these **Assets** and have easy access to information about them, such as how many times they are used in the **Project** or their location.

Furthermore, two **Nodes** for managing **Assets** in the **Asset Database** have been introduced:

* [**Add to Asset Database**](../toolbox/incari/asset/add-to-asset-database.md)
* [**Remove from Asset Database**](../toolbox/incari/asset/remove-from-asset-database.md)

![The Asset Database.](../.gitbook/assets/asset-db1.png)


## 2D Workflow Update

The previously introduced split of *2D* and *3D* components in **Incari** has been widely expanded in this current release. New [**Scene2D Objects**](#scene2d-objects) have been added, [**Prefabs**](#2d-prefabs) have been extended to be used in *2D* space, and **Scene2D Objects**  now allow for higher customizability using [CSS](#stylesheets).


### Scene2D Objects

New specific **Scene2D** **Objects** have been added along with their respective **Nodes**:

* [**Button**](../objects-and-types/scene2d-objects/gui/button.md)
* [**Dropdown**](../objects-and-types/scene2d-objects/gui/dropdown.md)
  * [**Get Active Dropdown Value**]()
  * [**Get Dropdown Options**]()
  * [**Set Active Dropdown Index**]()
  * [**Set Active Dropdown Value**]()
  * [**Set Dropdown Options**]()
  * [**On Dropdown Active Value Change**]()
* [**List**](../objects-and-types/scene2d-objects/gui/list.md)
  * [**Add List Element**]()
  * [**Get Active Indes**]()
  * [**Get List Data**]()
  * [**Get List Element**]()
  * [**Insert List Element**]()
  * [**Remove List Element**]()
  * [**Set Active Index**]()
  * [**Set List Data**]()
  * [**Set List Element**]()
  * [**On List Active Index Change**]()
* [**Slider**](../objects-and-types/scene2d-objects/gui/slider.md)
  * [**Get Slider Value**]()
  * [**Set Slider Value**]()
  * [**On Slider Value Change**]()
* [**Text**](../objects-and-types/scene2d-objects/gui/text.md)
* [**Text Area**](../objects-and-types/scene2d-objects/gui/textarea.md)
* [**Text Input**](../objects-and-types/scene2d-objects/gui/textinput.md)
* [**Toggle**](../objects-and-types/scene2d-objects/gui/toggle.md)
  * [**Get CheckBox Value**]()
  * [**Set CheckBox Value**]()
  * [**On CheckBox Value Change**]()

### 2D Prefabs


**Prefabs** in **Scenes** have already been an important facet of **Incari**. Now these extend into **Scene2Ds** where all **Objects** and combinations of **Objects** can be converted into **Prefabs**.

### Stylesheets

It is now possible to customize **Scene2D Objects** using *Stylesheets*. This can be set:

* For the entire **Project** in [**Project Settings**](../modules/project-settings/style.md).
* For the whole [**Scene2D**](../objects-and-types/project-objects/scene2d.md) via its `CSS File` **Attribute**.
* For a specific [**Object**](../objects-and-types/scene2d-objects/README.md) via its `Class names` and `CSS` **Attributes**.

Moreover, new **Nodes** that allow the user to modify these **Attributes** via **Logic** have been introduced:

* [**Scene 2D**](../toolbox/incari/scene2d/README.md)
  * [**Get Stylesheet**](../toolbox/incari/scene2d/getstylesheet.md)
  * [**Merge To Stylesheet**](../toolbox/incari/scene2d/mergetostylesheet.md)
  * [**Set Stylesheet**](../toolbox/incari/scene2d/setstylesheet.md)
* [**Object 2D**](../toolbox/incari/object2d/README.md)
  * [**Add CSS Class Name**](../toolbox/incari/object2d/addcssclassname.md)
  * [**Get CSS Class Name**](../toolbox/incari/object2d/getcssclassnames.md)
  * [**Remove CSS Class Name**](../toolbox/incari/object2d/removecssclassname.md)
  * [**Set CSS Class Name**](../toolbox/incari/object2d/setcssclassnames.md) 



## Exporter Update

The [**Exporter**](../modules/exporter.md) now allows the user to export a **Project** onto a different platform than it was created. For example, it can now handle the case of exporting a **Project** from *Windows* to *Linux*. 

In addition, the **Exporter** offers the user the option to export only the used **Assets**, thus providing a way to export a **Project** using only the necessary resources. 

![The Exporter updated.](../.gitbook/assets/exporterimage5update.png)

## Communication Update

**Incari** has extended the options for the different communication protocols it supports:

* **Serial** now has the option to set delimiters for incoming messages. This can be configured in [**Project Settings**](../modules/project-settings/serial.md).
* *HTTPS* support has been added to the already implemented [**HTTP**](../toolbox/communication/http/README.md), for both client and server.
* For [**CAN**](../toolbox/communication/can/README.md), it is now possible for multiple connections to be configured. This is set in [**Project Settings**](../modules/project-settings/CAN.md).
* [**MAVLink**](../toolbox/communication/mavlink/README.md) is now a [Plugin](../modules/plugins/communication/mavlinkmanager.md).


## **New Nodes and Node Updates**

Besides the **Nodes** related to new features that are specified above, several new **Nodes** have been introduced with this release while some existent ones have had major updates. The list is given below:
