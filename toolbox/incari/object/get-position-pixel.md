# Overview

![The Get Position Pixel Node.](../../../.gitbook/assets/getpixelposition.png)

The **Get Position Pixel Node** returns the *x* and *y values* of a **2D** or **Vector2D Object's** `Position`.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`| **ObjectID** | The target **Object** whose `Position` you wish to return, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`| **ObjectID** |  The ID of the target **Object** whose `Position` you wish to return.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Position` | **Vector2** | A 2-dimensional **Vector** that contains the *x* and *y* `Position` *values* of the target **Object**. |

# See Also

* [**Get Rotation 2D**](get-rotation-pixel.md)
* [**Get Size Pixel**](get-size-pixel.md)
  

