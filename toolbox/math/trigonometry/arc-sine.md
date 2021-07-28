# Arc Sine

## Overview

![The Arc Sine Node](../../../.gitbook/assets/node-arc-sine.png)

The **Arc Sine Node** takes a single **Float** value, representing an angle, in degrees \(°\) or radians \(rad\), and returns its _arcsine_.

## Attributes

### Miscellanous

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Is Degree` | **Bool** | Determines whether or not the `Input` value is given in degrees \(°\) or radians \(rad\). |

### Inputs

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Default Value` | **Float** | The default value of `Input`, if no value is provided in the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to calculate the _arcsine_ of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the _logic branch_, once this **Node** has finished its execution. |
| `Output` | **Float** | The _arcsine_ of `Input`. |

## See Also

* [**Trigonometry**](./)
* [**Sine**](sine.md)
* [**Radian-Degree Converter**](radian-degree-converter.md)

## External Links

* [_Trigonometry_](https://www.khanacademy.org/math/trigonometry) on Kahn Academy.
* [_Sine, Cosine and Tangent_](https://www.mathsisfun.com/sine-Cosine-Tangent.html) on Maths is Fun.

