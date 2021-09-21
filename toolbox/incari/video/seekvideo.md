# Seek Video

## Overview

![The Seek Video Node.](../../../.gitbook/assets/seekvideo.png)

The **Seek Video** **Node** can be used to move to a certain timeframe of a specified video by providing a variable for the `Frame Number`.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |
| `Frame Number` | **Int** | The timeframe of the video the user wishes to reference. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Play Video**](playvideo.md)
* [**Pause Video**](pausevideo.md)
* [**Stop Video**](stopvideo.md)
* [**Is Video Playing**](isvideoplaying.md)

