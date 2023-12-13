## Current Limitations - 2023.2

There are a few small exceptions that should be noted in order to make sure everything runs smoothly and renders properly when importing *Figma* projects into **Incari Studio**.

* **General**

  * Any flattened *Figma* objects, or *Figma* vectors in general, must not consist of multiple different fills.

* **Objects**

  * Polygons and Stars in *Figma* are imported as **Vectors**.

* **Text**

  * In *Figma*, properties are on a letter basis, meaning that it is possible to change the colors of individual letters. In **Incari** they are on an object basis, meaning that setting the color of individual letters won't do anything. A text imported from *Figma* to **Incari** will have a uniform color across all letters.

  * **Fonts** have to be added [manually](../modules/project-settings/fonts.md). If a font unknown to **Incari** is imported from a *Figma* project, a so-called *dummy font* will be used in its place and a file will appear in the **Asset Manager** containing default dummy font. 

  * `Line Height` only works with %, not with pt.

* **Frame**

  * Only integers for layouting. This may change in the coming days though

  * If the user imports a **Frame** which has a fixed size and its content (i.e. padding, gap, size, etc.) exceeds the size of the **Frame**, it will appear differently to how it looks in *Figma*. *Figma* tries to center the content while applying gap and padding; however, in **Incari Studio**, We apply the left and top padding and then the gap, and only apply the bottom and right padding for the space that remains.

* **Prefabs**

  * In *Figma* every instance can change what variant it is. In nested instances, the inner instances must not change the type of variant they use. If there is a change, everything upwards in the hierarchy will imported as a **Frame**. 

  * Remote *Figma* components are imported as **Frames**, so there is no linking to the original component.
  
  * For nested structures, if a *Figma* component has multiple variants, these variants will be imported as individual **Prefabs**, requiring separate **Logic** for each. This defeats the purpose of **Prefabs** so it is highly suggested to create only one variant per component in *Figma*. This variant would have all possible objects and properties, which the user can cluster into groups if necessary, and will be imported into **Incari** as one **Prefab**. This preserves the structure of the **Prefab**, especially in regard to any subsequent **Logic**. 


* **Vector**

  * Objects which cannot have a fill (open objects) have a static stroke width which cannot be changed. 

* **Paint**

  * Setting the *Outer Handle* of gradients is not supported.

  * *Diamond Gradient* paints are not supported, lending the whole layer to be nonexistant as nothing is imported.