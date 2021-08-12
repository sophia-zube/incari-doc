# Overview

![The Get RectangleCorners Node.](../../../../.gitbook/assets/getrectanglecorners.png)

The **Get RectangleCorners Node** returns the **Corners** of a **Rectangle Object** created in the **Scene Outliner Module** under *Vector*. **Corners** are **Vector2** type variables.  

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The target **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`RectangleCorners`|**Vector2**| The **RectangleCorners** of the target **Object**.|


# See Also

* [**Set RectangleCorners**](setrectanglecorners.md)

