# Set Alpha

## Overview

![The Set Alpha Node.](../../../.gitbook/assets/node-set-alpha.png)

**Set Alpha** sets the value of a specified **Object's** `Alpha` **Attribute** .

The **Set Alpha** **Node** only works with **Objects** that have **Attributes** from the **Sprite** category, such as [**List**](../../../objects-and-types/scene-objects/list-widget.md), **Image Sequence**, **Web Sprite**, [**Sprite**](../../../objects-and-types/scene-objects/sprite.md), and [**Text**](../../../objects-and-types/scene-objects/text.md).

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

## Attributes

![The Set Alpha Node Attributes.](../../../.gitbook/assets/node-set-alpha-attr.png)


| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object**, whose `Alpha` you wish to set, if one is not provided in the `Object ID` **Socket**. |
| `Default Alpha` | **Float** | The default value of the **Object** color space's `Alpha` component. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the **Object** whose `Alpha` value you would like to set. |
| `Alpha` | **Float** | The desired value of the **Object's** `Alpha` **Attribute**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Get Alpha**](get-alpha.md)

## External Links

* [_Alpha compositing_](https://en.wikipedia.org/wiki/Alpha_compositing) on Wikipedia.

