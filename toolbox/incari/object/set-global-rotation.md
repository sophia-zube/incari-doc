# Overview

![The Set Global Rotation Node.](../../../.gitbook/assets/setglobalrotation.png)

The **Set Global Rotation Node** assigns the global coordinates (in reference to the origin)  for a **3D Object's** *global rotation* in **Vector3** form.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose `Global Rotation` you wish to assign, if one is not provided in the `Object ID` **Socket**.|
|`Rotation`|**Vector3**| A 3-dimensional **Vector** that provides the X, Y, and Z _global rotation_ values for the target **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Global Rotation` you wish to assign.|
|`Rotation`|**Vector3**| A 3-dimensional **Vector** that provides the X, Y, and Z _global rotation_ values for the target **Object**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

