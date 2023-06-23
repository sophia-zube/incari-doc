# Scene2D

![](../../.gitbook/assets/scene2dimage.png)

A **Scene2D** is a collection of *2D* **Objects** that represent different unique places within your *User Interface*, such as menus, maps, and media players. Each **Scene2D** exists in two dimensions in pixel space. 

The workspace is only in two dimensions. For the order of **Objects**, an index is no longer required. Whatever way the **Objects** are listed in the **Scene Outliner** -- chosen by the user -- decides the order in which they are displayed.  

The **Scene2D Object** has a couple of **Attributes**:

* `Player Camera`: Determines the **Camera** that will show the **Scene2D** when the **Scene2D** starts. <!-- See [**Camera**](../scene-objects/camera.md) for more info on **Camera Objects**. -->
* `CSS File`: A *CSS* file which is applied to the particular **Scene2D**. It allows the user to style all **Scene2D Objects** with anything possible in [*CSS2*](https://en.wikipedia.org/wiki/CSS), such as making changes to font, background color, border, etc. It is also possible to trigger animations with the "transition" property, like smooth highlighting of a button when you hover or press it. However, when a **Scene2D Object** has its own *CSS* file, this lower level stylesheets take precedence over any higher level ones. 
