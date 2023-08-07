# Creating and Using Prefabs

## Introduction

A **Prefab** is composed of a collection of **Objects** that can be instantiated several times. Each of these **Instances** acts like a single **Object** and can retain unique properties via overrides. The characteristics that are shared through all **Instances** of a **Prefab** are managed from the **Prefab Asset** which is generated whenever a **Prefab** is created. Changes made in the **Prefab Asset** are enacted across all **Instances**.

**Prefabs** are available in both **Scenes** and **Scene2Ds**. They are treated virtually the same within **Projects**, just having dominion over different **Object** types. 

**Prefabs** in **Scene2Ds** are treated as [**Frames**](../../scene2d-objects/frame.md), but with the properties of a **Prefab**. However, on the surface, they essentially work the same as **Prefabs** in **Scenes**.

This section shows how to get started with **Prefabs**. It first describes how **Prefabs** can be created and how to edit them thus modifying all **Instances** of the **Prefab**. This is followed by a description of how to edit one single **Prefab Instance**. Finally, how to unpack **Prefabs** is explained. See how this works in both **Scenes** and **Scene2Ds**:

* [**Prefabs in Scenes**](3D.md)
* [**Prefabs in Scene2Ds**](2D.md)