# Overview

![The Set Active Index Node.](../../../.gitbook/assets/setactiveindexnode.png)

The **Set Active Index Node** sets the value of a **List's** `Active Index` **Attribute**.

The `Active Index` of a [**List**](../../../objects-and-types/scene2d-objects/gui/list.md) is the place of the active item in its order. Indexing starts at 0, so if the very first element of the **List** is the active item, the `Active Index` would be 0.  

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **List** the user wishes to set the `Active Index` for.|
|`Active Index`|**Int**|The value of the **List's** `Active Index` **Attribute**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get Active Index**](getactiveindex.md)

