# Sine

## Overview

![The Sine Node](../../../.gitbook/assets/node-sine.png)

The **Sine Node** takes a single **Float** value, representing an angle, in degrees \(°\) or radians \(rad\), and returns its _sine_.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Is Degree` | **Bool** | Determines whether the `Input` value is given in degrees \(°\) or radians \(rad\). |
| `Default Value` | **Float** | The default value of `Input`, if no value is provided in the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to calculate the _sine_ of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The _sine_ of `Input`. |

## See Also

* [**Trigonometry**](./)
* [**Arc Sine**](arc-sine.md)
* [**Radian-Degree Converter**](radian-degree-converter.md)

## External Links

* [_Trigonometry_](https://www.khanacademy.org/math/trigonometry) on Khan Academy.
* [_Sine, Cosine and Tangent_](https://www.mathsisfun.com/sine-Cosine-Tangent.html) on Maths is Fun.

