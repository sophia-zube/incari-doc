---
description: Available since 2022.1.2
---

# Overview

![The Insert Array Element Node.](../../.gitbook/insertarrayelementnode.png)

The **Insert Array Element Node** adds an element with a certain value at a specified index. It is also possible to insert multiple elements.

For example, an **Array** is populated as follows: $[0,6,12]$. If the `Indices` $1$ and $3$ are given and the values $3$ and $9$ are defined, the elements at those indices are inserted and the user is left with a new **Array**: $[0,3,6,9,12]$. 

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The Insert Array Element Node Attributes.](../../.gitbook/insertarrayelementattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Inputs`|**Drop-down**|Specifies each new element's `Index` in the **Array**, `Data Type`, and `Value`, if none are provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Array`|**Array**|The starting **Array** to have element(s) added.|
|`Index (0)`|**Int**|The index, or indices, where the element(s) should be inserted.|
|`Value`|**Int**|The value(s) of the element(s) to be added.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Array`|**Int**|The resulting **Array** with the inserted element(s).|
