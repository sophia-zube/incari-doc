## Current Limitations - 2023.2

There are a few small exceptions that should be noted in order to make sure everything runs smoothly and renders properly when importing *Figma* projects into **Incari Studio**.


| Feature |        |         |        |  2023.2  | 2024.1 |
| ------- | ------ | ------- | ------ | -------- | ------ |
| Object Blend Mode |    |    |       |   ✔       |     ✔  |
| Paint Layers      |     |   |       |    --      |    ✔   |
|            |  Modes |       |       |    --      |    ✔   |
|            |        | Color |       |   ✔       |    ✔   |
|            |        | Image |       |   ✔       |    ✔   |
|            |        |       |  Fill |   ✔       |    ✔   |
|            |        |       |  Fit  |    ✔      |    ✔   |
|            |        |       |  Crop |   --       |    --   |
|            |        |       |  Tile |   ✔       |    ✔   |
|            |        | Gradient|     |    --      |    --   |
|            |        |       | Linear|    --      |    ✔   |
|            |        |       | Radial|    --      |    ✔   |
|            |        |       | Angular|   --      |    ✔   |
|            |        |       |Diamond |   --      |    ✔   |
|            |        | Video |       |    ✘     |    ✔   |
|            |Layering|       |       |    ✔      |    ✔   |
|            |Opacity |       |       |    ✔      |    ✔   |
|            |Blendmodes|     |       |    ✔      |    ✔   |
|Mask        |         |      |       |    ✔      |    ✔   |
|            | Alpha   |      |       |    ✔      |    ✔   |
|           | Luminance|      |       |    ✔      |    ✔   |
|            | Shape   |      |       |    ✔      |    ✔   |
|Boolean     |         |      |       |    ✔      |    ✔   |
|            | Union   |      |       |    ✔      |    ✔   |
|            | Substraction|  |       |    ✔      |    ✔   |
|            | Intersection|  |       |   ✔       |    ✔   |
|            | Exclusion |    |       |   ✔       |    ✔   |
|Objects     |          |     |       |   --       |    ✔   |
|            | Vector   |     |       |   ✔       |    ✔   |
|            | Ellipse  |     |       |   ✔       |    ✔   |
|            | Line     |     |       |   ✔       |    ✔   |
|            | Frame    |     |       |   ✔       |    ✔   |
|        |       |Horizontal Layout|  |   ✔       |    ✔   |
|        |       |Vertical Layout  |  |   ✔       |    ✔   |
|        |       |Grid Layout |       |   ✘      |    ✘   |
|        |     |Gap & Padding |       |   ✔       |    ✔   |
|            | Crop     |     |       |   ✔       |    ✔   |
|            | Polygon  |     |       |   --       |    --   |
|            | Star     |     |       |   --      |    --   |
|            | Text     |     |       |   --       |    ✔    |
|            |       | Resizing |     |    ✘      |    ✔    |
|            |      | Font Family |   |    ✔      |    ✔    |
|            |   | Variable Fonts |   |    ✘      |    ✔    |
|            |          | Size |      |    ✔      |    ✔    |
|            |   | Line Height   |    |    --      |    ✔    |
|            |   | Letter Spacing|    |    ✔      |    ✔    |
|            |  | Paragraph Spacing|  |    ✔      |    ✔    |
|          |   |Horizonal Alignment|  |    ✔      |    ✔    |
|          |   |     | Left, Center, Right|  ✔    |    ✔    |
|          |   |Vertical Alignment |  |    ✔      |    ✔    |
|          |   |     | Top, Center, Bottom |  ✔   |    ✔    |
|          |   | Decoration |         |    ✘      |    ✘    |
|          |   |      | None          |    ✘      |    ✘    |
|          |   |     | Underlined     |    ✘      |    ✘    |
|          |   |     | Strikethrough  |    ✘      |    ✘    |
|          |   |Case  |               |    ✘      |    ✘    |
|          |   |     | As Typed       |    ✘      |    ✘    |
|          |   |     | Upper Case     |    ✘      |    ✘    |
|          |   |     | Lower Case     |    ✘      |    ✘    |
|          |   |     | Title Case     |    ✘      |    ✘    |
|          |   |     | Small Caps     |    ✘      |    ✘    |
|          |   |     | Forces Small Caps |  ✘     |    ✘    |
|          |   | Truncate Text |      |   ✘       |    ✘    |
|          |   |     | Maximum Lines  |    ✘      |    ✘    |
|          |   |Number Monospace |    |   ✘       |    ✘    |
|          |   |Number Alignment |    |   ✘       |    ✘    |
|          |   |     | Lining    |        ✘      |    ✘    |
|          |   |     | Old Style |        ✘      |    ✘    |
|          |   |Settings on Letter Basis|  |  ✘   |    ✘    |
| Importer |   |      |                |   --      |    --    |
|          | Accessing |         |    |    ✔      |    ✔    |
|          | Import    |         |     |    --     |    --    |
|          |           | Prefabs |     |    --     |    --    |
|          |           | Scenes  |     |    ✔     |    ✔     |
|          | Reimport  |         |     |    --     |    --    |
|          |           | Prefabs |     |   --      |    --    |
|          |           | Scenes  |     |   --      |    --    |
| Strokes  |           |         |     |   --      |    --    |
|          | Style     |         |     |   --      |    --    |
|          |           | Dash    |     |   ✘      |    ✘    |
|          |           | Solid   |     |   ✔      |    ✔     |
|          | Intersection |      |     |   ✘      |    ✘     |
|          |           | Join    |     |   ✘      |    ✘    |
|          |           | Regular |     |   ✘      |    ✘    |
|          |           | Round   |     |   ✘      |    ✘    |
|          | Caps      |         |     |   ✘      |    ✘    |
|          |           | None    |     |   ✘      |    ✘    |
|          |           | Round   |     |   ✘      |    ✘    |
|          |           | Square  |     |   ✘      |    ✘    |
|          |           | Line Arrow |  |   ✘      |    ✘    |
|          |        | Triangle Arrow|   |    ✘     |    ✘    |
| Effects  |        |             |    |   ✘      |    ✔    |
|          | Blend Modes |       |     |   ✘      |    ✔    |
|          | Drop Shadow |       |     |   ✘      |    ✔    |
|          | Inner Shadow |      |     |   ✘      |    ✔    |
|          | Layer Blur   |      |     |   ✘      |    ✔    |
|          | Background Blur |   |     |   ✘      |    ✔    |
| Constraints |          |       |     |   ✘      |    ✔    |
|      | Left, Center, Right |    |    |   ✘      |    ✔    |
|      | Top, Center, Bottom |     |   |   ✘      |    ✔    |
|      | Scale |         |             |   ✘      |    ✔    |
| Variant      |         |     |       |   ✘      |   ✘    |   



* **General**

  * Any flattened *Figma* objects, or *Figma* vectors in general, must not consist of multiple different fills.
  * *Effects* and *Constraints* are not supported. 

* **Objects**

  * Polygons and Stars in *Figma* are imported as **Vectors**.
  * Rotation is not considered when an **Object** is layouted. The unrotated **Object** is used as a basis for layouting. This is unlike *Figma*, where the rotated **Object** is used.

* **Text**

  * In *Figma*, properties are on a letter basis, meaning that it is possible to change the colors of individual letters. In **Incari** they are on an object basis, meaning that setting the color of individual letters won't do anything. A text imported from *Figma* to **Incari** will have a uniform color across all letters.

  * **Fonts** have to be added [manually](../../modules/project-settings/fonts.md). If a font unknown to **Incari** is imported from a *Figma* project, a so-called *dummy font* will be used in its place and a file will appear in the **Asset Manager** containing default dummy font. 

  * `Line Height` only works with %, not with *pt*.
  * Multiple *Figma* text configurations are not supported, e.g. *Case*, *Decoration*, etc.

* **Frame**

  * Only integers are used for layouting. 

  * If the user imports a **Frame** which has a fixed size and its content (i.e. padding, gap, size, etc.) exceeds the size of the **Frame**, it will appear differently to how it looks in *Figma*. *Figma* tries to center the content while applying gap and padding; however, in **Incari Studio**, we apply the left and top padding and then the gap, and only apply the bottom and right padding for the space that remains. Otherwise, the content is potentially moved out of the **Frame** on the right and bottom.

* **Prefabs**

  * In *Figma* every instance can change what variant it is. In nested instances, the inner instances must not change the type of variant they use. If there is a change, everything upwards in the hierarchy will be imported as a **Frame**. 

  * Remote *Figma* components are imported as **Frames**, so there is no linking to the original component.
  
  * For nested structures, if a *Figma* component has multiple variants, these variants will be imported as individual **Prefabs**, requiring separate **Logic** for each. This defeats the purpose of **Prefabs** so it is highly suggested to create only one variant per component in *Figma*. This variant would have all possible objects and properties, which the user can cluster into groups if necessary, and will be imported into **Incari** as one **Prefab**. This preserves the structure of the **Prefab**, especially in regard to any subsequent **Logic**. 


* **Vector**

  * Objects which cannot have a fill (open objects) have a static stroke width which cannot be changed. 

* **Paint**

  * *Video* paints are not supported, in stroke nor fill. This means that no paint will be imported.
  * Multiple stroke configurations are not supported, e.g. *Style*, *Intersection*, *Caps*, etc.