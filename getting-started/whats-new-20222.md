# What's New

Many new features have been added to the release of **Incari Studio** 2022.2. Here is a list of the features you need to know.

* **New Camera System**

    The new camera system...
    Camera object [add link]
    Camera nodes [add links]: Set Active Camera, Get Active Camera, Get Cameras

* **2D Workflow**

    *2D* Workflow...

* **Virtual Reality and Mixed Reality**

    Virtual Reality/Mixed Reality

* **Viewport**

    Now the **ViewPort**...

* [**Tags**](../objects-and-types/attributes/common-attributes/tag.md)

    A new **Attribute** has been introduced for all **Objects** in **Incari**: *Tags*. *Tags* are simple labels linked to **Objects** and are managed in the **Attribute Editor**, where they can be created, deleted, and edited. These *tags* allow the user to group and link different **Objects** under the same *tag*.

    There are also **Nodes** that allow the user to manage *tags* in the **Logic**. These are:

    * [**Add Tag**](../toolbox/incari/object/add-tag.md), which adds a *tag* to an **Object**.
    * [**Get Objects By Tag**](../toolbox/incari/object/get-objects-by-tag.md), which gives all **Objects** that share a specified *tag*.
    * [**Remove Tag**](../toolbox/incari/object/remove-tag.md), which removes a *tag* from an **Object**.

 
* **New Objects**

    Introducing New **Objects**...
    
* [**Structure of Objects in a Scene**](../objects-and-types/scene-objects/README.md#structure-in-a-scene)

    [**Objects**](../objects-and-types/scene-objects/README.md) in a [**Scene**](../objects-and-types/project-objects/scene.md) now have the structure of a *tree*. This means that every **Object** except for the [**Root Object**](../objects-and-types/scene-objects/README.md#root-object) has a *parent* and that all **Objects** may have *children*. Furthermore, any **Object** can be made into the *child* of any other **Object** in the **Scene**.    



* **New Nodes and Node Updates**

    New **Nodes**:
        * IO: Create File, Get Current Directory, Get File Extension, List Directory Contents, Remove, Set Current Directory
        * Objects: Destroy Object, Get Children, Get Name, Get Parent, Get Root, Has Children, Instantiate Object, Remove Tag
        * Math: Round
    
    **Nodes** updates: mouse global events

