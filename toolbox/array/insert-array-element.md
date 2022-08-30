---
description: Available from 2022.1.2
---

# Overview

![The Insert Array Element Node.]()

The **Insert Array Element Node** adds an element at a specified index.

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

<!---# Attributes

|Attribute|Type|Description|
|---|---|---|
--->
# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Array`|**Array**|The starting **Array** to have element(s) added.|
|`Indices`|**Int**|The index, or indices, where the element(s) should be inserted.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Array`|**Int**|The resulting **Array** with the inserted element(s).|
