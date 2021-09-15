As *Incari* can use both **2D** and **3D** **Assets**, it is necessary that the coordinate system is **3D**. The downside of this is that most designers work with a layer-based, 2D coordinate system which presents the need to convert each **Asset’s** position in 2D space to the same relative position in 3D. This can be a slow and tedious process.

With the introduction of **Screen** **Space** **Elements**, though, it is much easier for UI/UX designers using 2D-based tools to transfer their designs into *Incari* without the extra step of performing individual conversions. Designers can now import **Assets** from third-party content creation software, such as *Photoshop* or *Figma*, direcly into *Incari*.

The **2D** **Objects** available in *Incari* fall under two groups in the **Scene Outliner**. These are **2D** and **Vector2D**. These provide 2D counterparts to those under **3D** and **Vector3D** and are only editable within two-dimensional space, meaning that their position is only contained within the *x* and *y* axes. 

# 2D

![2D Objects](../../.gitbook/assets/2Delements.png)

The **2D Objects** cover different functional items used to provide engaging graphics and visuals in *Incari*.

* **Image Sequence Sprite2D** 

Image Sequences are used for one type of animation in *Incari*. More information can be found [*here*](https://docs.incari.com/incari-studio/demo-projects/4-methods-of-animation#3-image-sequence) and [*here*](../../modules/image-sequence-editor.md).

* **Label2D**

**Labels** are useful for identifying textual information and titles. More information can be found [*here*](../../toolbox/incari/vector/label/README.md).

* **List2D**

**Lists** require several different files to display data in the desired manner and are interwoven with *Incari* **Models**. More information can be found [*here*](list-widget.md).

* **On-Screen Keyboard2D**

As the name suggests, the **On-Screen Keyboard** is simply a keyboard shown on the screen in two-dimensional format. Certain style aspects can be changed with a .css file and `Tint`, which provides the color for the highlighted key. 

* **Sprite2D**

More information on **Sprite** **Objects** and further links can be found [*here*](sprite.md). 

* **Svg2D**

This **Object** allows the user to upload their own **SVG**, or *Scalable Vector Graphic*, file. Learn more about **Scalable Vector Graphics** on [*Wikipedia*](https://en.wikipedia.org/wiki/Scalable_Vector_Graphics).

* **Text2D**

A **Text Object** is used for writing texts in the **User Interface**. More information can be found [*here*](text.md)

* **Video2D**

**Videos** are self-explanatory. This **Object** allows the user to upload their own video and move it around within two-dimensional space. 

* **Web Sprite2D**

Web Sprites are important for embedding different types of web technologies into an *Incari* **Project**. This is explained in greater detail [*here*](https://docs.incari.com/incari-studio/v/2021.3-unreleased/getting-started/scene-objects/web-sprite).

# Vector2D 

![Vector2D Objects](../../.gitbook/assets/2Dvectorelements.png)

The **Vector2D Objects** provide alternatives to their **Vector** counterparts and encompass several two-dimensional shapes that help build up the visual aspects of a **User Interface**. Unlike **Vector**, **Vector2D Objects** do not have *z axis* capabilities. 

* **Arc2D**

A 2D **Object** that is a piece of a circle defined by a starting and ending degree disregarding the center and running straight through between the two selected degree points. It is retricted to the *x* and *y* *axes*. 

* **Ellipse2D**

A circular 2D **Object** that is restricted to the *x* and *y* *axes*.

* **Line2D**

A linear 2D **Object** that is restricted to the *x* and *y* *axes*.

* **Pie2D**

A 2D **Object** that is a piece of a circle defined by a starting and ending degree and comes to a point at the center of the circle. It is restricted to the *x* and *y* *axes*. 

* **Rectangle2D**

A rectangular 2D **Object** that is restricted to the *x* and *y* *axes*. 