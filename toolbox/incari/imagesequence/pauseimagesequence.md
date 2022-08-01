# Pause ImageSequence

## Overview

![The Pause ImageSequence Node.](../../../.gitbook/assets/node-pause-imagesequence.png)

**Pause ImageSequence** pauses an **ImageSequence** already playing during the session.

*Scope*: **Scene**, **Function**, **Prefab**

## Attributes

![The Pause ImageSequence Node Attributes.](../../../.gitbook/assets/node-pause-imagesequence-attr.png)

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
* [**Stop ImageSequence**](stopimagesequence.md)
* [**Resume ImageSequence**](resumeimagesequence.md)

