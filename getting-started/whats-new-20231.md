# What's New

Many new features have been added to the release of **Incari Studio** 2022.2. Here is a list of the features you need to know.


## 2D Workflow Update

The previously introduced split of *2D* and *3D* components in **Incari** has been widely expanded in this current release. 


### 2D Objects

New specific *2D* **Objects** have been added along with their respective **Nodes**:

* [**Button**](../objects-and-types/scene2d-objects/gui/button.md)
* [**Dropdown**](../objects-and-types/scene2d-objects/gui/dropdown.md)
  * [**Get Active Dropdown Value**]()
  * [**Get Dropdown Options**]()
  * [**Set Active Dropdown Index**]()
  * [**Set Active Dropdown Value**]()
  * [**Set Dropdown Options**]()
  * [**On Dropdown Active Value Change**]()
* [**List**](../objects-and-types/scene2d-objects/gui/list.md)
* [**Slider**](../objects-and-types/scene2d-objects/gui/slider.md)
* [**Text**](../objects-and-types/scene2d-objects/gui/text.md)
* [**Text Area**](../objects-and-types/scene2d-objects/gui/textarea.md)
* [**Text Input**](../objects-and-types/scene2d-objects/gui/textinput.md)
* [**Toggle**](../objects-and-types/scene2d-objects/gui/toggle.md)

### 2D Prefabs


**Prefabs** in **Scenes** have already been an important facet of **Incari**. Now these extend into **Scene2Ds** where all **Objects** and combinations of **Objects** can be converted into **Prefabs**.

### Stylesheets

now in Scene2D, Project Settings, and Objects 2D. Particular Nodes for Scene2D and Objects 2D

## Custom Shader 

The [**Material Editor**]() now includes a new shading model called the [**Custom Shader**](). It allows the user to create and customize their own shading model. This expands the possibilities for **Materials** in **Incari**. 

The customization is done via `Vertex Shader` or `Fragment Shader`. 

![Custom Shader Example.]()

## Exporter Update

The **Exporter** now allows the user to export a **Project** onto a different platform than it was created. For example, it can now handle the case of exporting a **Project** from *Windows* to *Linux*. 

In addition, the **Exporter** offers the user the option to export only the used **Assets**, thus providing a way to export a **Project** using only the necessary resources. 

![New Exporter.]()

## Communication Update

* Serial has new options in **Project Settings**
* HTTPS supported
* CAN now allows for multiple Connections
* MAVLink is now in Plugins

## Asset Database

new!!

## **New Nodes and Node Updates**

Besides the **Nodes** related to new features that are specified above, several new **Nodes** have been introduced with this release while some existent ones have had major updates. The list is given below:

