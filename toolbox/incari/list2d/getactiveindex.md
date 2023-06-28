# Overview

![The Get Active Index Node.](../../../.gitbook/assets/getactiveindex.png)

The **Get Active Index Node** returns the value of a **List's** `Active Index` **Attribute**.

The `Active Index` of a [**List**](../../../objects-and-types/scene2d-objects/gui/list.md) is the place of the active item in its order. Indexing starts at 0, so if the very first element of the **List** is the active item, the `Active Index` would be 0. 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **List** the user wishes to get the `Active Index` from.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Active Index`|**Int**|Returns the value of the **List's** `Active Index` **Attribute**.|

# See Also

* [**Set Active Index**](setactiveindex.md)