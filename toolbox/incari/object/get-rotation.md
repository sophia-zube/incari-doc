# Get Rotation

## Overview

![The Get Rotation Node.](../../../.gitbook/assets/getrotationupdatedimage.png)

**Get Rotation** returns the _rotation_ of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get Rotation Node Attributes.](../../../.gitbook/assets/node-get-rotation-attr.png)


| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**, whose `Rotation` you wish to return, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Rotation` value you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Rotation` | **Vector3** | A 3-dimensional vector that contains the `Rotation` components measured in Euler angles along the X, Y, and Z axes of the target **Object**. |

## See Also

* [**Get Scale**](get-scale.md)
* [**Get Position**](get-position.md)
* [**Set Rotation**](set-rotation.md)

## External Links

* [_Rotation_](https://en.wikipedia.org/wiki/Euler_angles) on Wikipedia

