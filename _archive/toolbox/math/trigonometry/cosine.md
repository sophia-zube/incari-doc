# Cosine

## Overview

![](../../../.gitbook/assets/node-cosine.png)

The **Cosine Node** takes a single **Float Value**, representing an angle, in degrees \(°\) or radians \(rad\), and returns its _cosine_.

_Cosine_ is a _trigonometric function_, used to calculate the acute angles and side lengths of right-angled triangles. Trigonometry has a vast amount applications, ranging from engineering to astronomy. The most relevent to INCARI, though, is that it can be used to calculate cooridnates and distances within 3D space.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Is Degree` | **Bool** | Determines whether or not the `Input` **Value** is given in degrees \(°\) or radians \(rad\). |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Float** | The angle to calculate the _cosine_ of. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Float** | The _cosine_ of `Input`. |

## External Links

* [_Trigonometry_](https://www.khanacademy.org/math/trigonometry) on Kahn Academy.
* [_Sine, Cosine and Tangent_](https://www.mathsisfun.com/sine-cosine-tangent.html) on Maths is Fun.

