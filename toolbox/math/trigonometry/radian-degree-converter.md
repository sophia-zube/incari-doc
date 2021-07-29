# Radian-Degree Converter

## Overview

![The Radian-Degree Converter Node](https://github.com/cgi-studio-gmbh/incari-doc/tree/65634e5b4b0d3223401be6b27a11f0a6872da087/.gitbook/assets/node-radian-degree-converter.png)

**Radian-Degree Converter** takes a single **Float** value, representing an angle, in degrees \(°\) or radians \(rad\), and converts it from one unit to the other.

The equation used by the **Node** is determined by the `Mode` **Attribute**. The equations are:

* `Radian_to_Degree` - _R_ x 180/π
* `Degree_to_Radian` - _D_ x π/180

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mode` | **Drop-down** | Determines which conversion equation is used. |
| `Default Value` | **Float** | The default value of `Input`, if no value is provided in the `Input` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to convert. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard output **Pulse**, to move onto the next **Node** along the _logic branch_, once this **Node** has finished its execution. |
| `Output` | **Float** | The converted value. |

## See Also

* [**Trigonometry**](./)

