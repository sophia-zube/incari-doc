# Overview

![The Get Active Index Node.](../../../.gitbook/assets/getactiveindex.png)

The **Get Active Index Node** returns the value of a **List's** `Active Item` **Attribute**.

[**Scope**](): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **List** the user wishes to get the `Active Index` from.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Active Index`|**Int**|Returns the value of the **List's** `Active Item` **Attribute**.|

# See Also

* [**Set Active Index**](setactiveindex.md)