# Play Video

## Overview

![The Play Video Node.](../../../.gitbook/assets/playvideo.png)

The **Play Video** **Node** can be used to play a specified video file during the session. This can be added through the file library to the right or as a **Scene Object** by way of `ObjectID`.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **Object ID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **Object ID** | The ID of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |


## See Also

* [**Stop Video**](stopvideo.md)
* [**Pause Video**](pausevideo.md)
* [**Seek Video**](seekvideo.md)
* [**Is Video Playing**](isvideoplaying.md)
