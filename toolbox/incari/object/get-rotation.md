# Get Rotation

## Overview

![The Get Rotation Node.](../../../.gitbook/assets/get-rotation.PNG)

**Get Rotation** returns the _rotation_ of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object** that you wish to return the `rotation` of, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose _rotation_ value you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Rotation` | **Vector3** | A 3-dimensional vector that contains _Euler rotation_ on the x, y, and z axes of the target **Object**. |

## See Also

* [**Get Scale**](get-scale.md)
* [**Get Position**](get-position.md)
* [**Set Rotation**](set-rotation.md)

## External Links

* [_Rotation_](https://en.wikipedia.org/wiki/Euler_angles) on wikipedia

