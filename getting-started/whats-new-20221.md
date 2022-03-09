# What's New

Many new features have been added to the release of **Incari Studio** 2022.1. Here is a list of the features you need to know.

* **Global and Local Transfrom** 

    Originally, it was only possible to make changes in global space (i.e. in relation to the origin). Now it is possible to make object transformations locally in relation to the object itself. For example, if the user wishes to rotate an object around itself, this is now much easier with local transform. Switch the toggle `LocalMode` to enable and disable this feature. There are several **Nodes** attached to this new feature. 

  * [**On Local Position Change**]
  * [**On Local Rotation Change**]
  * [**Set Local Position**]
  * [**Get Local Position**]
  * [**Set Local Rotation**]
  * [**Get Local Rotation**]
  * [**On Global Position Change**]
  * [**On Global Rotation Change**]
  * [**Set Global Position**]
  * [**Get Global Postion**]
  * [**Set Global Rotation**]
  * [**Get Global Rotation**]


* **Flip Normals** 

    To aid in providing a more immersive experience, `Flip Normals`, located under `Normals` for an **Object** in the **Attribute Editor** can help. When the toggle is switched on, it is possible to see an applied **Material** from within an **Object**. The user can rotate, move, and scale as usual. 


* **`.glTF` files**

     **Incari** now supports `.glTF` files, extending the abilities of user interface design within **Incari Studio**. 

<!--
* **Material Editor Update**
  
   environment, normal maps, occlusion map, new pbr material (extended pbr material)???

!-->

* **Prefabs**
    **Prefabs** are now available in **Incari**. This is a useful feature that allows the user to create multiple individual instances of an interactive **Object** in a user interface and then make changes that are enacted across all instances. For example, to create several buttons that change color when a mouse hovers over it, right-click and select `Make prefab`, and duplicate as many types as necessary. To make edits to the **Prefab**, simply locate it in the **Asset Manager** and double-click to open up a special **Prefab Init** window. These edits will overrride the properties changed, but unique properties will remain. It is easy to share with others or between projects with the `Export prefab` option in the **Asset Manager**. All **Assets** inside a **Prefab** will be put together into a directory on export. 

    Within **Prefab Init**, there are two **Nodes** which allow the user to apply **Logic** to a prefab.
        * [**Prefab Input**]
        * [**Prefab Output**]



* **Plugins** 
  
    **Serial Manager Communication** can be activated or disactivated here. When disactivated, **Incari Player** will not load anything related to **Serial Communication** in order to improve performance and stability. Stay tuned for more updates to **Communication** within **Incari**.  




* [**Format Node**] -

* [**HTTP Client Node Update**]

    The **HTTP Client Node** has been overhauled and now uses an external library. In addition, it can now support *HTTPS*. 





