# Get Position Pixel

## Overview

![The Get Position Pixel Node.](../../../.gitbook/assets/getpixelposition.png)

The **Get Position Pixel Node** returns the _X_ and _Y values_ of a **2D Object's** `Position`.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object** whose `Position` you wish to return, if one is not provided in the `Object ID` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Position` you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | A 2-dimensional **Vector** that contains the _X_ and _Y_ `Position` _values_ of the target **Object**. |

## See Also

* [**Get Rotation 2D**](get-rotation-pixel.md)
* [**Get Size Pixel**](get-size-pixel.md)

