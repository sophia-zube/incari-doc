# Show ImageSequence Frame

## Overview

![The Show ImageSequence Frame Node.](../../../.gitbook/assets/node-show-imagesequence-frame.png)

**Show ImageSequence Frame** displays the frame at the selected index.

*Scope*: **Scene**, **Function**, **Prefab**

## Attributes

![The Show ImageSequence Frame Node Attributes.](../../../.gitbook/assets/node-show-imagesequence-frame-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Frame` | **Int** | The index of the desired frame. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

