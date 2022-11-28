# Pause Animation

## Overview

![The Pause Animation Node.](../../../.gitbook/assets/pauseanimationupdatedimage.png)

**Pause Animation** is an **Animation** **Node** used to pause an **Animation** already playing. It receives as input the [**Instance ID**](README.md#instance-id) of the **Animation** to be paused.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Instance ID` | **InstanceID** | The [**Instance ID**](README.md#instance-id) of the **Animation** to be paused. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Play Animation**](playanimation.md)
* [**Stop Animation**](stopanimation.md)

