# Play Animation

## Overview

![The Playanimation Node.](../../../.gitbook/assets/playanimation.png)

**Play Animation** is an _animation_ **Node** that can be found under **Incari** in the node library and a **CustomID** type variable is required as input. It is used to play an **Animation** when the project is run and can be used in conjunction with **Pause Animation** and **Stop Animation**

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `File` | **User Input** | The animation file the user wishes to manipulate. The user can drag a file from their library or select a file from a file tree. The icons to the right allow for the user to confirm selection, highlight the **Asset** in the **Asset Manager**, and remove the selection. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| _InstanceID_ | **CustomID** | The assigned **Instance** of the **Animation** |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| _InstanceID_ | **CustomID** | The previously assigned **Instance** of the **Animation** |
| _OnPlay_ | **Pulse** | Flows to additional actions following **Play Animation** |
| _OnPause_ | **Pulse** | Flows to additional actions following **Play Animation** \(most likely **Pause Animation** |
| _OnStop_ | **Pulse** | Flows to additional actions following **Play Animation** \(most likely **Stop Animation**\) |

