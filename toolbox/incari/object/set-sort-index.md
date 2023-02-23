# Overview

![The Set Sort Index Node.](../../../.gitbook/assets/setsortindex.png)

The **Set Sort Index Node** sets the sort index of an **Object**, which is the order an **Object** is layered in a **Scene**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** of interest.|
|`Sort Index`|**Int**|The integer value of the desired sort index for the inputted **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get Sort Index**](get-sort-index.md)
