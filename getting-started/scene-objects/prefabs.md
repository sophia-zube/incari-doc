# Prefabs

## Overview

**Prefabs** are a feature that allow to create multiple individual instances of a combination of **Objects** in a *User Interface*, and then make changes that are enacted across all instances. This allows one to easily create several **Objects** with the same functionality that retain unique properties via overrides. Moreover, **Prefabs** have their own **Logic** encapsulated within them. Any alterations in the **Prefab** properties or its **Logic** affect all of its instances.

## Creating and Using Prefabs

For creating a **Prefab**, go to the **Scene Outliner** and select the **Objects** that will compose the **Prefab**, then right-click and click on `Make Prefab`. This will create a **Prefab** consisting of the selected **Objects** and a new **Prefab** **Asset** will be generated in the **Asset Manager**.

![Creating a **Prefab**.](../../.gitbook/assets/prefabs1.gif)

New instances of the **Prefab** can be created by either duplicating the existing **Prefab** in the **Scene Outliner** or by dragging the **Prefab Asset** from the **Asset Manager** to the **Scene Outliner** or the **Scene**.

![Creating new instances of a **Prefab**.](../../.gitbook/assets/dupliprefabs.gif)

To edit the master **Prefab**, double-click the **Prefab** in the **Asset Manager**. This will open the **Prefab** view in both the **Scene Outliner** and **Attribute Editor**. The **Prefab** view is indicated by a purple circle. Changes made here affect all instances of the **Prefab**. 

![Editing the master **Prefab**.](../../.gitbook/assets/editmasterprefab.gif)

For the changes made in the master **Prefab** to take effect, it is necessary to save them by pressing the `Save prefab` button on the top right corner of the viewport.

![**Prefab** view.](../../.gitbook/assets/prefab-view.png)

Each instance of a **Prefab** can be modified on its own and this overrides the **Attributes** from the master **Prefab**. To do this, simply edit the **Object** in the **Prefab** instance.

![Prefab instance override.](../../.gitbook/assets/prefabinstanceoverride.gif) 


## Logic

**Prefabs** have their own **Logic** encapsulated within them and it applies to all instances of the **Prefab**. The **Prefab** **Logic** can be incorporated into the **Scene Logic** via a **Prefab Node**.

![Prefab Node.](../../.gitbook/assets/prefab-node.png)

To open the **Prefab Logic** graph in the **Logic Editor** either double click the **Prefab Node** in the **Logic Editor** or the **Prefab Asset** in the **Asset Manager**.

The **Prefab Logic** has two **Nodes** by default: **Prefab Input** and **Prefab Output**. These represent the **Input** and **Output** of the **Prefab Node**.

![Prefab Logic](../../.gitbook/assets/prefab-logic.png)





## Example

example - buttons






