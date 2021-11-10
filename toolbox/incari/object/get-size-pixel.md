# Get Size Pixel

## Overview

![The Get Size Pixel Node.](../../../.gitbook/assets/getsizepixel.png)

The **Get Size Pixel Node** returns the X and Y values of a **2D Object's** `Size`.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object** whose `Size` you wish to return, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Size` you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Size` | **Vector2** | A 2-dimensional **Vector** that contains the _X_ and _Y_ `Size` _values_ of the target **Object**. |

## See Also

* [**Get Position Pixel**](get-position-pixel.md)
* [**Get Rotation 2D**](get-rotation-pixel.md)

