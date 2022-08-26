# Get Scale

## Overview

![The Get Scale Node.](../../../.gitbook/assets/node-get-scale.png)

**Get Scale** returns the _scale_ of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get Scale Node Attributes.](../../../.gitbook/assets/node-get-scale-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**, whose `Scale` you wish to return, if one is not provided in the `Object ID` **Socket** |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Scale` value you wish to return. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Scale` | **Vector3** | A 3-dimensional **Vector** that contains the `Scale` of the **Object** along its X, Y, and Z axes. |

## See Also

* [**Get Rotation**](get-rotation.md) 
* [**Get Position**](get-position.md)

## External Links

* [_Scaling \(geometry\)_](https://en.wikipedia.org/wiki/Scaling_%28geometry%29) on Wikipedia.

