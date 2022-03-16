# Overview

![The Get Global Position Node.](../../../.gitbook/assets/getglobalposition.png)

The **Get Global Position Node** returns the global coordinates (in reference to the origin)  for a **3D Object's** *global position* in **Vector3** form.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose global `Position` you wish to return, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose global `Position` you wish to return. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Position` | **Vector3** | A 3-dimensional **Vector** that contains the X, Y, and Z _global position_ values of the target **Object**. |

# See Also

* [**Get Global Rotation**](get-global-rotation.md)
* [**Set Global Position**](set-global-position.md)
* [**Set Global Rotation**](set-global-rotation.md)