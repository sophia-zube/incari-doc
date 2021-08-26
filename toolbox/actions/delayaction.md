# Delay Action

## Overview

![The Delay Action Node.](../../.gitbook/assets/delayaction.png)

The **Delay Action Node** delays the **Action** for the specified duration \(in seconds\).

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Duration (sec)` | **Float** | The total time of the **Action**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance** of an **Object**. |
| \(►\) `Start` | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Duration` | **Float** | The total time \(in seconds\). |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `Instance ID` | **InstanceID** | The assigned **Instance** of an **Object**. |
| `OnStart` \(►\) | **Pulse** | Flows to additional actions following **Delay Action** when the **Action** starts. |
| `OnEnd` \(►\) | **Pulse** | Flows to additional actions following **Delay Action** when the **Action** stops. |

