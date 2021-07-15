# Set Position

## Overview

![The Set Position Node.](../../../.gitbook/assets/set-position.PNG)

**Set Position** sets the value of a given **Object**'s `Position` **Attribute**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The ID of the **Object** that you would like to set the `Position` value of if one is not provided in the `Object ID` **Socket**. |
| `Position` | **Vector3** | The desired `Position` value of the **Object** if one is not provided in the `Position` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the **Object** that you would like to set the `Position` value of. |
| `Position` | **Vector3** | The desired `Position` value of the **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Get Rotation**](get-rotation.md)
* [**Get Scale**](get-scale.md)
* [**Get Position**](get-position.md)

## External Links

* \_\_[_Position \(geometry\)_](https://en.wikipedia.org/wiki/Position_%28geometry%29) on Wikipedia.

