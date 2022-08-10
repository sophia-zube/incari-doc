# Resume ImageSequence

## Overview

![The Resume ImageSequence Node.](../../../.gitbook/assets/node-resume-imagesequence.png)

The **Resume ImageSequence Node** restarts an **ImageSequence** after it has been paused or stopped.

[**Scope**](../overview.md#scopes):
*  **Scene**, **Function**, **Prefab**

## Attributes

![The Resume ImageSequence Node Attributes.](../../../.gitbook/assets/node-resume-imagesequence-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Play ImageSequence**](playimagesequence.md)
* [**Pause ImageSequence**](pauseimagesequence.md)
* [**Stop ImageSequence**](stopimagesequence.md)

