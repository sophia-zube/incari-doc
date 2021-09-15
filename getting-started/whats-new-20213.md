# What's New

With the release of Incari Studio 2021.3, there appeared a number of new features. Here is a list of the features you need to know.

* [**Primitives**](scene-objects/primitives.md)

    **Primitives** are new 3D objects available in *Incari* that can be altered to the visual specifications of the user. 

* [**Directional Lights**](scene-objects/lights.md)

    *Incari* has added a third type of **Light** that extends the capabilities of lighting and shadows in a **Scene**.

* [**Normal Maps**](../modules/material-editor.md)

    With **Normal Maps** now available in the **Materials Editor**, users of *Incari* can now take advantage of this texturing technique that will reduce rendering time and also improve the details of the **Mesh**.

* **Screen Space Elements**

* [**Build Module (version 1)**](../modules/exporter.md)
  
    This new **Module** allows to export a **Project** into a desired folder of the Host target and generate an execution file.

* [**CPU Profiler Integration**](../modules/profiler-view.md)
  
    _Incari_ has now a **Profiler** tool integrated, which allows to analyze the performance of any **Block** of **Nodes** in the **Logic**. To use it, a **Profiler Block** using the new [**Profiler Start**](../toolbox/development/profiler-start.md) and [**Profiler Stop**](../toolbox/development/profiler-stop.md) **Nodes** has to be created and then the [**Profiler View Module**](../modules/profiler-view.md) is used for capturing and analyzing the performance of the **Blocks**.

![](../.gitbook/assets/profiler-view-connected.png)

* **Compiler in Command Line Interface (version 1)**

    Now the **Logic** of a **Project** can be compiled directly from the command line. This allows to then directly run a **Project** in _Incari Player_ without having to open the **Project** in _Incari Studio_.
    
    The command to compile the **Logic** of a **Project** is: `IncariCLI.exe /p="<project-path>"`.