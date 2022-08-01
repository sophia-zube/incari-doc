# Get ImageSequence Total Frames

## Overview

![The Get ImageSequence Total Frames Node.](../../../.gitbook/assets/node-get-imagesequence-total-frames.png)

The **Get ImageSequence Total Frames Node** returns the total number of frames in the **ImageSequence**.

*Scope*: **Scene**, **Function**, **Prefab**

## Attributes

![The Get ImageSequence Total Frames Node Attributes.](../../../.gitbook/assets/node-get-imagesequence-total-frames-attr.png)

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
| `Frame Count` | **Int** | The total number of frames. |

## See Also

* [**Get Current ImageSequence Frame**](getcurrentimagesequenceframe.md)
* [**Get ImageSequence FPS**](getimagesequencefps.md)
* [**Get ImageSequence Duration**](getimagesequenceduration.md)

