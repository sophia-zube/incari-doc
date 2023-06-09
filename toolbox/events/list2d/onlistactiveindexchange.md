# Overview

![The On List Active Index Change Node.](../../../.gitbook/assets/onlistactiveindexchange.png)

The **On List Active Index Change** is an **Event Listener** **Node** used for executing a **Logic Branch** when a **List's** `Active Index` changes.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** in which an `Active Index` change triggers the **Logic Branch**.|
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Current Index`|**Int**|The current `Active Index`.|
|`Object ID`|**ObjectID**| The **Object** received as **Input**. |


