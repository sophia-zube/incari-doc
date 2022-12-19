# What's New

Many new features have been added to the release of **Incari Studio** 2022.2. Here is a list of the features you need to know.

* **New Camera System**

    The new camera system...
       
   * [**Camera Object**](../objects-and-types/scene-objects/camera.md) 
   * [**Camera 2D Object**](../objects-and-types/scene2d-objects/camera2d.md)

    **Camera Nodes**:
    
    * [**Get Active Camera**](../toolbox/incari/camera/get-active-camera.md)
    * [**Get All Cameras**](../toolbox/incari/camera/get-all-cameras.md)
    * [**Set Active Camera**](../toolbox/incari/camera/set-active-camera.md)

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

    This version of **Incari** introduces three new **Objects**. They are:
    
    * [**Audio**](../objects-and-types/scene-objects/audio.md)
        **Audio Objects** let the user incorporate aural information into a *User Interface*, such as music or recorded speech. Currently, only `.mp3` files are supported, but more formats are anticipated to follow in the future. 
    * [**Lottie Sprite**](../objects-and-types/scene-objects/lottie-sprite.md)
        **Incari** now has a way to display `.lottie` files, a very popular file format for animations. These **Objects** provide the user with extended possibilities for visual creativity within a *User Interface*.
    * [**Overlay**](../objects-and-types/scene-objects/overlay.md)
       Related to the new **2D Workflow**, **Overlay Objects** allow the user to mix 3D and 2D **Scenes** by overlaying 2D **Scenes** on top of 3D **Scenes**. 
    
* [**Structure of Objects in a Scene**](../objects-and-types/scene-objects/README.md#structure-in-a-scene)

    [**Objects**](../objects-and-types/scene-objects/README.md) in a [**Scene**](../objects-and-types/project-objects/scene.md) now have the structure of a *tree*. This means that every **Object** except for the [**Root Object**](../objects-and-types/scene-objects/README.md#root-object) has a *parent* and that all **Objects** may have *children*. Furthermore, any **Object** can be made into the *child* of any other **Object** in the **Scene**.    



* **New Nodes and Node Updates**

    New **Nodes**:
        * IO: Create File, Get Current Directory, Get File Extension, List Directory Contents, Remove, Set Current Directory
        * Objects: Destroy Object, Get Children, Get Name, Get Parent, Get Root, Has Children, Instantiate Object, Remove Tag
        * Math: Round
    
    **Nodes** updates: mouse global events

