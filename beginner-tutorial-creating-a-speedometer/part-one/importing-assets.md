# Importing Assets and Sort Order

To import graphics into INCARI, we simply drag and drop them from our OS's explorer, to the Asset Manager. Similarly, when we want to bring assets into our scene, we drag and drop them from the Asset Manager into our scene.

{% hint style="warning" %}
Because graphics in our scene occupy the same 3D space, INCARI has no way of automatically knowing which elements are in the foreground or the background. We can manually tell INCARI by selecting an object in the Scene Outliner and setting a "Sort Index" value in the Attribute Editor. Graphics are sorted from lower to higher, meaning that a graphic with an index of 1 would be shown above a graphic with an index of 0.
{% endhint %}

* Import the provided graphics into the Asset Manager.
* Drag them into the Scene View.
* Adjust the "Sort Index" of the graphics, so that they render correctly.

![](../../.gitbook/assets/4_assetimport-and-sort%20%281%29.gif)

## Rearranging Objects

**Objects** in INCARI's **Scene Outliner** are structured _hierarchically_. Your operating system's files are also hierarchically structured. Files can be placed into folders and when you move, delete or copy the folder, its sub-folders and files \(children\) contained within its hierarchy are also modified. Where INCARI differs is that an **Object** can also work like a folder and contain multiple sub-objects \(children\). Things like **Position**, **Rotation** and **Scale** of a _parent_ **Object** also affect all of the _children_ **Objects**.

To _rearrange_ an **Object** in the **Scene Outliner**, drag and drop it _between_ other **Objects**. To _parent_ an **Object** to another **Object**, drag and drop it _on top of_ another Object.

