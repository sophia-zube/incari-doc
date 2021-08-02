# Stop Animation

## Overview

![The Stop Animation Node.](../../../.gitbook/assets/stopanimation.png)

**Stop Animation** is an _animation_ **Node** used to stop an **Animation** already playing.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Enabled` | **Bool** | A toggle switch that allows the **Node** to be turned on or off. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `InstanceID` | **InstanceID** | The assigned **Instance** of an **Animation Block**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Pause Animation**](pauseanimation.md)
* [**Play Animation**](playanimation.md)

