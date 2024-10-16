# Overview

![The Get Active Dropdown Value Node.](../../../.gitbook/assets/getactivedropdownnode20241.png)

The **Get Active Dropdown Value Node** returns the value that is currently active of the inputted [**Dropdown Object**](../../../objects-and-types/scene2d-objects/gui/dropdown.md).

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Dropdown Object** whose active value will be returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Value`|**String**|The **Dropdown Object's** value which is currently active.|

# See Also

* [**Set Active Dropdown Value**](set-active-dropdown-value.md)



