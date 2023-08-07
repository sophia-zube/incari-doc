# Prefabs


**Prefabs** are **Objects** that are composed of a combination of **Objects**. They allow the user to create multiple individual **Instances** of this combination and then make changes that are enacted across all of them. Each **Instance** can also retain unique properties via overrides, thus allowing one to create several **Objects** with the same functionality but different characteristics. Moreover, **Prefabs** have their own **Logic** encapsulated within them.

There are two types of **Prefabs**, those available in **Scenes** and those available in **Scene2Ds**. They both can only encapsulate the **Objects** present in their respective **Scene** type. 

The first section shows how to create and use **Prefabs** in both **Scenes** and **Scene2Ds**. **Prefabs** in **Scene2Ds** are treated as **Frames**, but with the properties of a **Prefab**. The second section gives more details about the **Logic** of **Prefabs** and the third section describes **Nested Prefabs**. On the surface, **Prefabs** in **Scene2Ds** essentially work the same as **Prefabs** in **Scenes** so they follow the same procedures highlighted in the latter two sections.

## Contents

* [**Creating and Using Prefabs**](creatingandusingprefabs/README.md)
  * [**Prefabs in Scene2Ds**](creatingandusingprefabs/2D.md)
  * [**Prefabs in Scenes**](creatingandusingprefabs/3D.md)
* [**Logic in Prefabs**](logic-prefabs.md)
* [**Nested Prefabs**](nested-prefabs.md)

## See Also

* [**Prefabs Demo Project**](../../demo-projects/prefabs-demo.md)