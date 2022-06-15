# Incari Studio

**Incari Studio** is an all-in-one tool for the streamlined work of HMI (Human-Machine Interface) creation. It allows for quick UI (User Interface) prototyping and deployment.

![](../.gitbook/assets/incari-studio-initial.png)

In the usual case, there is a separation between design and development. On one side, developers have to implement the entire interface from source code, and then spend a lot of time reviewing results, adjusting animations, requesting new assets, and iterating the entire process. On the other side, designers may not be aware of software limitations such as animation types or others. With **Incari**, all necessary tools for building UI are available from the beginning. Designers can focus on the interface layout or the creation of animation while developers work on the logic and providing data sources, then both parts can be easily connected thus implementing the entire UI.

The main features of **Incari Studio** are:

   * It is easy to import and use designs from tools such as _Sketch_, _Figma_ or _Photoshop_.
   * The **Animation Editor** incorporated in **Incari** allows to create advanced animations of UI elements.
   * Features implementation can be easily reused, thus speeding up **Project** production.
   * It supports any input source, be it haptic, auditory, visual, or external from CAN, MQTT, HTTP.

![](../.gitbook/assets/incari-studio-end.png)

## Incari Player

**Incari Player** is the component that displays **Projects** created in **Incari Studio**. It runs as a stand-alone application in which **Incari** **Projects** can be loaded and played.

It can receive external communication from sources such as HTTP, Bluetooth, CAN bus, MQTT, NAV.

**Incari Player** is focused on performance and stability. For example, it does not waste GPU time in calculating elements that are not visible for the user. 

It supports multiple screens and out-of-the-box data synchronization between scenes, thus making it easy to have synchronized multi-screen animations or interaction between elements in differents screens.


## User Interface Overview

For a quick overview of the general interface in **Incari Studio**, we will use one of the **Demo Projects**.

First, we have to download it from the *Remote Projects* tab in **Incari Hub**, and then we can load it from the *My Projects* tab.

We choose the `methodsofanimation` **Project**. In the *Remote Projects* tab, we find it and click on the cloud to download it.

![](../.gitbook/assets/incari-hub-animationmethodschoice.png)

Then, the **Project** should appear in the *My Projects* tab, where we can load it by clicking on the play button that appears when we hover over the **Project**.

![](../.gitbook/assets/incari-hub-animationmethodsmyproj.png)

Now with the **Demo Project** loaded we can have a quick overview of the interface.

![](../.gitbook/assets/animationmethods-project.png)

The components of the interface in **Incari** are called **Modules**. Each one has a different purpose, in the next section we give an overview of their functionalities. **Modules** can be either visible or hidden. Choosing which ones are visible can be done by right-clicking the top bar and selecting or deselecting them. Moreover, **Modules** can also made visible from the `View` menu in the top bar and they can be hidden by clicking the `X` at the top right of each of them.

![](../.gitbook/assets/modulesmenu.png)

![](../.gitbook/assets/modulesviewmenu.png)

These **Modules** can be docked in the **Incari Studio** interface as the user prefers, thus allowing for a complete customization of the positions and sizes of the visible **Modules**. 

![](../.gitbook/assets/dockingmodules1.gif)

Moreover, **Modules** can be docked together and then accessed via the tabs that are automatically created.

![](../.gitbook/assets/dockingmodules2.gif)

**Modules** can be also used as independent windows, which can be very useful when working with more than one screen.

![](../.gitbook/assets/moduleindep.gif)

**Modules** that are individual windows can be locked so they do not dock on the main **Incari Studio** interface. This is done by clicking on the lock icon that appears on the top-right of a module that is being seen as an independent window.

![](../.gitbook/assets/dockingenable.png)


The **Viewport** shows what will be displayed when the **Project** is run and its look can be customized. For this, go to `Edit > Global Preferences > Viewport`.

![](../.gitbook/assets/viewport2.png)

![](../.gitbook/assets/viewport.png)