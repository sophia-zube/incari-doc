# Overview

![The Remove CSS Class Name Node.](../../../.gitbook/assets/removecssclassname.png)

**Remove CSS Class Name Node** deletes a *CSS class* with the given *name*. It has no effect if the given *class name* does not exist. 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** that the *CSS class name* will be removed from.|
|`Class Name`|**Class Name**|The desired *class name* to be removed.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|


# External Links

* Read for more information on [*CSS Selectors*](https://en.wikipedia.org/wiki/CSS#Selector).
