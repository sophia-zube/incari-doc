# Get ImageSequence Duration

## Overview

![The Get ImageSequence Duration Node.](../../../.gitbook/assets/getimagesequencedurationupdatedimage.png)

The **Get ImageSequence Duration Node** returns the total runtime \(in seconds\) of the **ImageSequence**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get ImageSequence Duration Node Attributes.](../../../.gitbook/assets/node-get-imagesequence-duration-attr.png)

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
| `Duration` | **Float** | The total runtime. |

## See Also

* [**Get ImageSequence FPS**](getimagesequencefps.md)
* [**Get ImageSequence Total Frames**](getimagesequencetotalframes.md)
* [**Get Current ImageSequence Frame**](getcurrentimagesequenceframe.md)

