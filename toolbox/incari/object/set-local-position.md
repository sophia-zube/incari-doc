# Overview

![The Set Local Position Node.](../../../.gitbook/assets/node-set-local-position.png)

The **Set Local Position Node** sets the *local position* values for a given **Object**.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**


# Attributes

![The Set Local Position Node Attributes.](../../../.gitbook/assets/node-set-local-position-attr.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose local `Position` you wish to assign, if one is not provided in the `Object ID` **Socket**.|
|`Position`|**Vector3**| A 3-dimensional **Vector** that provides the X, Y, and Z _local position_ values for the target **Object**, if one is not provided in the `Position` **Socket**. |

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

<!-- * [**Global and Local Transforms**]() -->
* [**Set Local Rotation**](set-local-rotation.md)
* [**Get Local Position**](get-local-position.md)
* [**Get Local Rotation**](get-local-rotation.md)

## External Links

* [_Position \(geometry\)_](https://en.wikipedia.org/wiki/Position_%28geometry%29) on Wikipedia.