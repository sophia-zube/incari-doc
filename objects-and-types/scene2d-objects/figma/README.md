# Vector

The **Vector Objects** in **Scene2Ds** implement some updated concepts in **Incari** which build upon the previous [**Vectors**](../vector2d.md) while incorporating functionalities seen in *Figma*. The purpose of this is to lend greater customizability to the user so that they are able to import *Figma* projects using the [**Figma Importer**](../../../modules/figma-importer.md) and continue making use of fills, strokes, masks, etc. in **Incari**. 

It is important to note that since **2023.2**, the old **Vector Objects** no longer appear in **Incari Studio**. They are also deprecated, meaning that while they may appear in older **Projects**, they are not supported. However, the documentation for them remains under [**Vector (old)**](../vector2d.md).

For certain *Figma* objects, such as a *Star* or *Polygon*, **Incari** will import them as a **Vector**. These **Vectors** are uneditable and unchangeable and therefore do not have a separate category. This subcategory is not to be confused with the aforementioned old **Vector Objects** nor the current main category.

Additionally, while all **Vector Objects** have the option to add a `Video` to its `Fill` **Attribute**, it is also possible to drag a **Video** from the **Asset Manager** into the **Scene2D**. This will automatically create a **Rectangle** with the same name as the **Video** and the **Video** will already be added as a `Fill`. 

# Contents

* [**Boolean Operation**](figmabooleanoperation.md)
* [**Ellipse**](figmaellipse.md)
* [**Line**](figmaline.md)
* [**Rectangle**](figmarectangle.md)
* [**Text**](figmatext.md)
