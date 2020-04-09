# Dynamically Changing the Transformation of an Object

Now that we have the **Speed Variable** mapped to a rotation value, we are going to apply it to our needle graphic. The transformations of **Objects** can be dynamically changed using the **Object Node**.

## Object Nodes

Changing **Transformation Attributes** of an **Object** in the **Attribute Editor** is useful for _static_ graphics, text and 3D objects, however we often need to adjust these values dynamically based on things like user interaction, menu changes, or in our case, changes in the value of a **Variable**. To be able to _get_ and _set_ the values of these **Objects**, we need to add an **Object Node**. This can be done conveniently, by dragging and dropping an item from the **Scene Outliner** to the **Logic Editor Graph.**



