# What's New

With the release of Incari Studio 2021.3, there appeared a number of new features. Here is a list of the features you need to know.

* [**Primitives**](scene-objects/primitives.md)

  **Primitives** are new 3D **Objects** available in **Incari** that can be altered to the visual specifications of the user.

* [**Directional Lights**](scene-objects/lights.md)

  **Incari** has added a third type of **Light** that extends the capabilities of lighting and shadows in a **Scene**.

* [**Normal Maps**](../modules/material-editor.md)

  With **Normal Maps** now available in the **Materials Editor**, users of **Incari** can now take advantage of this texturing technique that will reduce rendering time and also improve the details of the **Mesh**.

* [**Screen Space Elements**](scene-objects/screen-space-elements.md)

  **Screen Space Elements** will let users transfer their designs from third-party applications like _Photoshop_ and _Figma_ into **Incari** without requiring a tedious conversion process. Furthermore, versions of **3D** and **Vector** **Objects** editable only in two-dimensional space make an appearance under **2D** and **Vector2D** categories in the **Scene Outliner**, alongside new **Nodes**.

* [**Build Module \(version 1\)**](../modules/exporter.md)

  This new **Module** allows to export a **Project** into a desired folder of the Host target and generate an execution file.

* [**CPU Profiler Integration**](../modules/profiler-view.md)

  **Incari** has now a **CPU Profiler** tool integrated, which allows to analyze the performance of any **Block** of **Nodes** in the **Logic**. A **Profiler Block** with the new [**Profiler Start**](../toolbox/development/profiler-start.md) and [**Profiler Stop**](../toolbox/development/profiler-stop.md) **Nodes** has to be created first and then the [**Profiler View Module**](../modules/profiler-view.md) is used for capturing and analyzing the performance of the **Blocks**.

![](../.gitbook/assets/profiler-view-connected.png)

* **Compiler in Command Line Interface \(version 1\)**

  Now the **Logic** of a **Project** can be compiled directly from the command line. This allows to then directly run a **Project** in **Incari Player** without having to open the **Project** in **Incari Studio**.

  The command to compile the **Logic** of a **Project** is: `IncariCLI.exe /p="<project-path>"`.

