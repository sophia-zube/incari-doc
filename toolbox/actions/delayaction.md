# Delay Action

## Overview

![The Delay Action Node.](../../.gitbook/assets/node-delay-action-node.png)

The **Delay Action Node** performs a delay of the **Pulse Flow** for the specified duration \(in seconds\). 



## Attributes

![The Delay Action Node Attributes.](../../.gitbook/assets/node-delay-action-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Duration (sec)` | **Float** | The time of the delay. |


## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance ID** of the **Action**. If nothing is received, it automatically assigns 0 as the **Instance ID**.  |
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Duration` | **Float** | The time of the delay \(in seconds\). |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance ID** of the **Action**. |
| `OnStart` \(►\) | **Pulse** | Flows to the next **Node** following **Delay Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to the next **Node** following **Delay Action** when the **Action** stops. |

