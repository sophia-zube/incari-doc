# Overview

![The Interpolate Node.](../../.gitbook/assets/node-interpolate.png)

The **Interpolate** **Node** calculates intermediates values between an initial and target value over a set amount of time. It is particularly useful for animations.

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | The numerical data type which will be interpolated. |
| `Duration (s)` | **Float** | The length of time between the start and end of the interpolation, if it is not provided in the `Duration (s)` **Socket**. |
| `Interval Time (s)` | **Float** | How frequently the interpolated value is updated and the output **Pulse** is triggered.|
| `From` | **Float** | The value at the start of the interpolation, if one is not provided in the `From` **Socket**. |
| `To` | **Float** | The value at the end of the interpolation, if one is not provided in the `To` **Socket**.|

## Interpolation

|Attribute|Type|Description|
|---|---|---|
| `Type` | **Drop-down** | Method used for calculating the intermediate values. |
| `Mode` | **Drop-down** | Whether the interpolation will be performed once, repeated or alternated. |
| `Count`| **Int** (_not available for `Mode` Once_) | The number of times that the interpolation will be performed, if it is not provided in the `Count` **Socket**. |
| `Infinite` | **Bool** | Whether the interpolation will be played indefinitely (this overrides the `Count` **Attribute**). |
# Inputs

|Input|Type|Description|
|---|---|---|
| `Instance ID` | |
| `Start` | **Pulse** | Triggers the start of the interpolation. |
| `Duration (s)` | **Float** | The length of time between the start and end of the interpolation. |
| `Count` | **Int** | The number of times that the interpolation will be performed. |
| `From` | **Float** | The value at the start of the interpolation. |
| `To` | **Float** | The value at the end of the interpolation. |
| `Reset` | **Pulse** | Resets the interpolation. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Instance ID` |  |
| `Value` | **Float** |
| `OnStart` | **Pulse** |
| `OnReset` | **Pulse** |
| `OnEnd` | **Pulse** |

# See Also

# External Links

