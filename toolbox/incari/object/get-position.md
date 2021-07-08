# Get Position

## Overview

![The Get Position Node.](../../../.gitbook/assets/get-position.PNG)

**Get Position** returns the _position_ of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object** that you wish to return the `position` of, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose _position_ you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector3** | A 3-dimensional vector that contains x, y, and z positions of the target **Object**. |

## See Also

* [**Get Rotation**](get-rotation.md)
* [**Get Scale**](get-scale.md)
* [**Set Position**](../set-current-index/set-position.md)

## External Links

* \[_Positioning_\]\([https://en.wikipedia.org/wiki/Position\_\(geometry](https://en.wikipedia.org/wiki/Position_%28geometry)\)\) in geometry.

