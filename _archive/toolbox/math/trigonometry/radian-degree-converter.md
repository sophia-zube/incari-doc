# Radian-Degree Converter

## Overview

![](../../../.gitbook/assets/node-radian-degree-converter.png)

**Radian-Degree Converter** takes a single **Float Value**, representing an angle, in degrees \(°\) or radians \(rad\), and converts it from one unit to the other.

The equation used by the **Node** is determined by the `Mode` **Attribute**. The equations are:

* Radians to Degrees - _R_ x 180/π
* Degrees to Radians - _D_ x π/180

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mode` | **Drop-down** | Determines which conversion equation is used. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to to convert. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The converted **Value**. |

