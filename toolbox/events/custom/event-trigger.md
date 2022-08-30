# Event Trigger

## Overview

![The Event Trigger Node.](<../../../.gitbook/assets/eventnode - Copy.png>)

**Event Trigger** is a **Custom Event Node** used for triggering an **Event**, which then activates the corresponding **Custom Event Listener Node**.

The number, type, and default value of the **Input** parameters can be set in the **Event** **Attributes**.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

## Inputs

| Input             | Type          | Description                                                           |
| ----------------- | ------------- | --------------------------------------------------------------------- |
| _Pulse Input_ (►) | **Pulse**     | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Parameter [n]`   | **Drop-down** | `Parameter` that will be passed on to the **Listener** **Node**.      |

## See Also

* [**Custom**](./)
* [**Event Listener**](event-listener.md)
