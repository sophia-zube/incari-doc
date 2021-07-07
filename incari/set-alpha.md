# Set Alpha

## Overview

![The Set Alpha Node.](../.gitbook/assets/set-alpha.PNG)

**Set Alpha** sets the value of a specified **Object**'s `Alpha` **Attribute** .

The **Set Alpha** **Node** only works with **Objects** that have **Attribute**'s from the **Sprite** category, such as **List**, **Image Sequence**, **Web Sprite**, **Sprite**, and **Text**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** you wish to set the `Alpha` of if one is not provided in the `Object ID` **Socket**. |
| `Default Alpha` | **Float** | The default value of the **Object** color space's `alpha` component. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the **Object** whose `Alpha` value you would like to set. |
| `Alpha` | **Float** | The desired value of the **Object**'s `Alpha` **Attribute**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

[**Get Alpha**](get-alpha.md)

## External Links

* [_Alpha value_](https://en.wikipedia.org/wiki/Alpha_compositing)

