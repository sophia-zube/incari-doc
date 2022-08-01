# Overview

![The Get Global Rotation Node.](../../../.gitbook/assets/getglobalrotation.png)

The **Get Global Rotation Node** returns the global coordinates (in reference to the origin)  for a **3D Object's** *global rotation* in **Vector3** form. 

*Scope*: **Scene**, **Function**, **Prefab**

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose global `Rotation` you wish to return, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose global `Rotation` you wish to return. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Rotation` | **Vector3** | A 3-dimensional **Vector** that contains the X, Y, and Z _global rotation_ values of the target **Object**. |

# See Also

* [**Get Global Position**](get-global-position.md)
* [**Set Global Position**](set-global-position.md)
* [**Set Global Rotation**](set-global-rotation.md)