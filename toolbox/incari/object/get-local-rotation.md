# Overview

![The Get Local Rotation Node.](../../../.gitbook/assets/node-get-local-rotation.png)

The **Get Local Rotation Node** returns the *local rotation* of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

# Attributes

![The Get Local Rotation Node.](../../../.gitbook/assets/node-get-local-rotation-attr.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose local `Rotation` you wish to return, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object** whose local `Rotation` you wish to return. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Rotation` | **Vector3** | A 3-dimensional **Vector** that contains the local `Rotation` components measured in Euler angles along the X, Y, and Z axes of the target **Object**. |

# See Also

<!-- * [**Global and Local Transforms**]() -->
* [**Get Local Position**](get-local-position.md)
* [**Set Local Position**](set-local-position.md)
* [**Set Local Rotation**](set-local-rotation.md)

## External Links

* [_Rotation_](https://en.wikipedia.org/wiki/Euler_angles) on Wikipedia