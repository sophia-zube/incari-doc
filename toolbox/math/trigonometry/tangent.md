# Tangent

## Overview

![The Tangent Node](https://github.com/cgi-studio-gmbh/incari-doc/tree/65634e5b4b0d3223401be6b27a11f0a6872da087/.gitbook/assets/node-tangent.png)

The **Tangent Node** takes a single **Float** value, representing an angle, in degrees \(°\) or radians \(rad\), and returns its _tangent_.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Is Degree` | **Bool** | Determines whether or not the `Input` value is given in degrees \(°\) or radians \(rad\). |
| `Default Value` | **Float** | The default value of `Input`, if no value is provided in the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to calculate the _tangent_ of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the _logic branch_, once this **Node** has finished its execution. |
| `Output` | **Float** | The _tangent_ of `Input`. |

## See Also

* [**Trigonometry**](./)

## External Links

* [_Trigonometry_](https://www.khanacademy.org/math/trigonometry) on Kahn Academy.
* [_Sine, Cosine and Tangent_](https://www.mathsisfun.com/sine-Cosine-Tangent.html) on Maths is Fun.

