# Overview

![The Set Local Position Node.](../../../.gitbook/assets/setlocalposition.png)

The **Set Local Position Node** assigns the local coordinates (in reference to the **Object** itself)  for a **3D Object's** *local position* in **Vector3** form.


# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose local `Position` you wish to assign, if one is not provided in the `Object ID` **Socket**.|
|`Position`|**Vector3**| A 3-dimensional **Vector** that provides the X, Y, and Z _local position_ values for the target **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose local `Position` you wish to assign.|
|`Position`|**Vector3**| A 3-dimensional **Vector** that provides the X, Y, and Z _local position_ values for the target **Object**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Set Local Rotation**](set-local-rotation.md)
* [**Get Local Position**](get-local-position.md)
* [**Get Local Rotation**](get-local-rotation.md)
