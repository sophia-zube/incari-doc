# Asset Database

## Overview

The **Asset Database** is a *database* of all the **Assets** that are either used in the **Project** or available to be used at runtime. It allows the user to keep track of all these **Assets** and have easy access to information about them, such as how many times they are used in the **Project** or their location.

In summary, the **Asset Database** shows two sets of **Assets**:

* **Assets** that are currently used in the **Project**. These are added automatically when used in the **Project**.
* **Assets** that are available to be used in the **Project** at runtime. These have to be added manually from the [**Asset Manager**](asset-manager.md).

![](../.gitbook/assets/asset-db1.png)

For each **Asset**, the **Asset Database** displays the following information:

* `ID`: Unique identifier for the **Asset**.
* `Icon`: Icon that represents the `Type` of **Asset**.
* `Type`: Type of **Asset**.
* `Label`: *Label* for the **Asset**. By default, it is set to the filename and it can be edited directly on the **Asset Database**.
* `Source`: The origin of an **Asset**.
* `Path`: *Path* to the file. For **Assets** located in the **Project Asset** folder, it shows the relative *path*, and for other **Assets**, it shows the full *path*.
* `#`: Number of times that the **Asset** is used in the **Project**.

And it offers two options:

* `Highlight asset in Asset Manager`: Press this option to highlight the **Asset** in the **Asset Manager**.
* `Remove asset from Asset Database`: Press this option to remove the **Asset** from the **Asset Database**.



## Adding Assets to the Asset Database

There are three ways in which **Assets** can be added to the **Asset Database**: [Using **Assets** in the **Project**](#using-assets-in-the-project), [manually](#manually), or [using **Logic**](#at-runtime-using-logic). 

### Using Assets in the Project

Using an **Asset** automatically adds it to the **Asset Database**.

![](../.gitbook/assets/asset-db-addtoproject.gif)

### Manually

An **Asset** can be added manually to the **Asset Database**. To do this, simply drag and drop a file in the **Asset Database**. This can be done from the **Asset Manager** or from the *File Explorer*, thus allowing to add files that are not in the **Asset** folder.

There are three special cases:

* **Keyboard Layouts** have to be added in [**Project Settings**](project-settings/keyboard.md) and then they will be automatically added to the **Asset Database**. 

* **Fonts** have to be added in [**Project Settings**](project-settings/fonts.md) and then they will be automatically added to the **Asset Database**.

* **Materials** are automatically added to the **Asset Database** when created in the [**Asset Manager**](asset-manager.md) 

![](../.gitbook/assets/asset-db-addmanually.gif)

### At runtime using Logic

**Assets** can be added to the **Asset Database** using **Logic**. For this purpose, use the [**Add to Asset Database** **Node**](../toolbox/incari/asset/add-to-asset-database.md), which receives the *path* of the file to be added to the **Asset Database**.

<!-- They can then be removed from the **Asset Database** using the [**Remove from Asset Database** **Node**](../toolbox/incari/asset/remove-from-asset-database.md). To obtain the **Node** corresponding to an **Asset** in the **Asset Database**, simply drag the **Asset** from the **Asset Database** into the **Logic Editor**. -->

See in the image below a simple example of how to add an **Asset** to the **Asset Database** in the **Logic**, using, besides the **Add to Asset Database** **Node**, the [**String Value** **Node**](../toolbox/string/stringvalue.md):

![](../.gitbook/assets/assetdb-in-logic2.png)


## Features

The **Asset Database** offers several features that are useful for managing **Assets**. These are: [search](#search), [filter](#filter), [highlight use](#highlight-use), [highlight in **Asset Manager**](#highlight-in-asset-manager) and [remove](#remove).

### Search

The search bar on the top right of the **Asset Database** allows the user to search **Assets** by either `ID` or `Label`.


![](../.gitbook/assets/assetdb-search.gif)

### Filter

The filter on the top right of the **Asset Database** allows the user to filter the **Assets** by `Type`.

![](../.gitbook/assets/assetdb-filter.gif)

### Highlight use

By clicking on the `ID` of an **Asset**, its use in the **Scene Outliner** and **Viewport** will be highlighted.

![](../.gitbook/assets/assetdb-highlightuse.gif)

### Highlight in Asset Manager

By clicking on the magnifying glass on an **Asset** entry, this **Asset** will be highlighted in the **Asset Manager**.

![](../.gitbook/assets/assetdb-highlight.gif)

### Remove

To remove an **Asset** from the **Asset Database**, click on the minus on far right of an **Asset** entry.

![](../.gitbook/assets/assetdb-remove.gif)

