# What's New

Many new features have been added to the release of **Incari Studio** 2022.2. Here is a list of the features you need to know.

* **New Camera System**

    On this release, a new **Camera** system has been introduced. With it, each **Scene** comes with a default **Camera** **Object** that is set to be the **Scene's** **Player Camera**, which is the **Camera** used when a **Scene** is initialized. This can be configured in the **Scene's** **Attributes**. 

    Now, **Camera** **Objects** are treated as any other **Object** in **Incari** and the view of a **Scene** is configured directly in them. Moreover, any number of **Cameras** can be used in a **Scene** and be managed through the evolution of a **Scene** in the **Logic** with the new **Camera Nodes**.

    **Camera Objects** have now new features:

    * **Picture-in-Picture**: By selecting a **Camera** in the **Scene Outliner**, the user can see in the bottom right corner of the **Viewport** how the **Scene** looks like through that **Camera**.
    * **Look Through**: Mode that allows the user to see in the **Viewport** what a **Camera** shows.
    * **Proxies**: **Cameras** in the **Viewport** are displayed with their **Proxies**, which show which part of the **Scene** they will render.

    See more about **Camera Objects**:
       
   * [**Camera Object**](../objects-and-types/scene-objects/camera.md) 
   * [**Camera 2D Object**](../objects-and-types/scene2d-objects/camera2d.md)

    **Camera Nodes**:
    
    * [**Get Active Camera**](../toolbox/incari/camera/get-active-camera.md)
    * [**Get All Cameras**](../toolbox/incari/camera/get-all-cameras.md)
    * [**Set Active Camera**](../toolbox/incari/camera/set-active-camera.md)

* **2D Workflow**

    Previously in **Incari**, *2D* and *3D* components coexisted in the same space. However, workflow was very *3D*-oriented, regardless of the dimensionality of an **Object**. Now **Incari** offers **Scene2Ds** alongside **Scenes**. **Scenes** continue to provide whatever a user would need in 3D space. **Scene2Ds** supply the user with the option for a *2D* workflow, providing an imperative facet to *User Interface* design. 

    In **Scene2Ds**, the workspace is truly only in two dimensions, in pixel space. For the order of **Objects**, an index is no longer required. Whatever way the **Objects** are listed in the **Scene Outliner** -- chosen by the user -- decides the order in which they are displayed.  

    Since *2D* and *3D* are now treated separately in **Incari**, [**Overlay Objects**](../objects-and-types/scene-objects/overlay.md) have been created to bridge this so-called gap. This way, the user can specify a **Scene2D** to be rendered on top of a 3D **Scene**. 

    3D **Scene Objects** are explained in detail [here.](../objects-and-types/scene-objects/README.md) There are also several [**2D Objects**](../objects-and-types/scene2d-objects/README.md) attributed to the **Scene2D** side of workflow in **Incari**. 


* **Virtual Reality and Mixed Reality**

    Virtual Reality/Mixed Reality

    

    

<!-- * **Viewport**

    Now the **ViewPort**...
 -->
* [**Tags**](../objects-and-types/attributes/common-attributes/tag.md)

    A new **Attribute** has been introduced for all **Objects** in **Incari**: *Tags*. *Tags* are simple labels linked to **Objects** and are managed in the **Attribute Editor**, where they can be created, deleted, and edited. These *tags* allow the user to group and link different **Objects** under the same *tag*.

    There are also **Nodes** that allow the user to manage *tags* in the **Logic**. These are:

    * [**Add Tag**](../toolbox/incari/object/add-tag.md), which adds a *tag* to an **Object**.
    * [**Get Objects By Tag**](../toolbox/incari/object/get-objects-by-tag.md), which gives all **Objects** that share a specified *tag*.
    * [**Remove Tag**](../toolbox/incari/object/remove-tag.md), which removes a *tag* from an **Object**.

 
* **New Objects**

    This version of **Incari** introduces three new **Objects**. They are:
    
    * [**Audio**](../objects-and-types/scene-objects/audio.md):  
        The new **Audio Objects** let the user incorporate aural information into a *User Interface*, such as music or recorded speech. Currently, only `.mp3` files are supported, but more formats are anticipated to follow in the future.

    * [**Lottie Sprite**](../objects-and-types/scene-objects/lottie-sprite.md):
        **Incari** now has a way to display `.lottie` files, a very popular file format for animations. These **Objects** provide the user with extended possibilities for visual creativity within a *User Interface*.
        Moreover, **Nodes** for managing *Lottie* animations as well as **Event Nodes** that are triggered by *Lottie* animations have been introduced:
         * [**Play Lottie**](../toolbox/incari/lottie/play-lottie.md)
         * [**Pause Lottie**](../toolbox/incari/lottie/pause-lottie.md)
         * [**Stop Lottie**](../toolbox/incari/lottie/stop-lottie.md)
         * [**On Lottie Play**](../toolbox/events/lottie/on-lottie-play.md)
         * [**On Lottie Pause**](../toolbox/events/lottie/on-lottie-pause.md)
         * [**On Lottie Stop**](../toolbox/events/lottie/on-lottie-stop.md)
         * [**On Lottie Finish**](../toolbox/events/lottie/on-lottie-finish.md)

    * [**Overlay**](../objects-and-types/scene-objects/overlay.md):
       Related to the new **2D Workflow**, **Overlay Objects** allow the user to mix 3D and 2D **Scenes** by overlaying 2D **Scenes** on top of 3D **Scenes**. 
    
* [**Structure of Objects in a Scene**](../objects-and-types/scene-objects/README.md#structure-in-a-scene)

    [**Objects**](../objects-and-types/scene-objects/README.md) in a [**Scene**](../objects-and-types/project-objects/scene.md) now have the structure of a *tree*. This means that every **Object** except for the [**Root Object**](../objects-and-types/scene-objects/README.md#root-object) has a *parent* and that all **Objects** may have *children*. Furthermore, any **Object** can be made into the *child* of any other **Object** in the **Scene**.

    **Nodes** to retrieve information about the **Scene Structure** were introduced as well:

    * [**Get Children**](../toolbox/incari/object/get-children.md)
    * [**Get Parent**](../toolbox/incari/object/get-parent.md)
    * [**Get Root**](../toolbox/incari/object/get-root.md)
    * [**Has Children**](../toolbox/incari/object/has-children.md)



* **New Nodes and Node Updates**

    Besides the **Nodes** related to new features that are specified above, several new **Nodes** have been introduced with this release while some existent ones have had major updates. The list is given below:

    New **Nodes**:
      * **IO**: 
        * [**Create File**](../toolbox/io/createfile.md)
        * [**Get Current Directory**](../toolbox/io/getcurrentdirectory.md)
        * [**Get File Extension**](../toolbox/io/getfileextension.md)
        * [**List Directory Contents**](../toolbox/io/listdirectorycontent.md)
        * [**Remove Object**](../toolbox/io/remove.md)
        * [**Set Current Directory**](../toolbox/io/setcurrentdirectory.md)
      * **Objects**: 
        * [**Destroy Object**](../toolbox/incari/object/destroy.md)
        * [**Get Name**](../toolbox/incari/object/get-name.md)
        * [**Instantiate Object**](../toolbox/incari/object/instantiate.md)
      * **Math**: 
        * [**Round**](../toolbox/math/round.md)
      * **Mouse**:
        * [**Get Mouse Position**](../toolbox/events/mouse/getmouseposition.md)
        * [**Get Mouse Position Delta**](../toolbox/events/mouse/getmousepositiondelta.md)
      * **Leap Motion**:
        * [**On Leap Motion Grab End**](../toolbox/events/leapmotion/on-leapmotion-grab-end.md)
        * [**On Leap Motion Grab Start**](../toolbox/events/leapmotion/on-leapmotion-grab-start.md)
        * [**On Leap Motion Grab Update**](../toolbox/events/leapmotion/on-leapmotion-grab-update.md)
        * [**On Leap Motion Pinch End**](../toolbox/events/leapmotion/on-leapmotion-pinch-end.md)
        * [**On Leap Motion Pinch Start**](../toolbox/events/leapmotion/on-leapmotion-pinch-start.md)
        * [**On Leap Motion Pinch Update**](../toolbox/events/leapmotion/on-leapmotion-pinch-update.md)
        * [**On Leap Motion Swipe Left**](../toolbox/events/leapmotion/on-leapmotion-swipe-left.md)
        * [**On Leap Motion Swipe Right**](../toolbox/events/leapmotion/on-leapmotion-swipe-right.md)
    
    **Nodes** with major updates:
      * [**Mouse Event Nodes**](../toolbox/events/mouse/README.md): The new **Attribute** `Event Base` has been introduced for all **Mouse Event Nodes**. With it, the user can set the **Node** to work for a particular **Object** or in the entire **Scene**.
        * [**On Mouse Button Down**](../toolbox/events/mouse/on-mouse-button-down.md)
        * [**On Mouse Button Up**](../toolbox/events/mouse/on-mouse-button-up.md)
        * [**On Mouse Click**](../toolbox/events/mouse/on-mouse-click.md)
        * [**On Mouse Double Click**](../toolbox/events/mouse/on-mouse-double-click.md)
        * [**On Mouse Enter**](../toolbox/events/mouse/on-mouse-enter.md)
        * [**On Mouse Leave**](../toolbox/events/mouse/on-mouse-leave.md)
        * [**On Mouse Move**](../toolbox/events/mouse/on-mouse-move.md)
        * [**On Mouse Scroll**](../toolbox/events/mouse/on-mouse-scroll.md)
 
    

