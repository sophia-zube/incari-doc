# Overview

![The Set CheckBox Value Node.](../../../.gitbook/assets/setcheckboxvaluenode20241.png)

The **Set Checkbox Value** sets the **Boolean** value for a [**Toggle Object**](../../../objects-and-types/scene2d-objects/gui/toggle.md) depending on if the user wants it to be checked on or off.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The desired **Toggle Object**.|
|`Value`|**Boolean**|The **Boolean** value to be set. This is either *true* if the **Toggle Object** should be checked on, or *false* if not.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get CheckBox Value**](get-checkbox-value.md)
* [**On CheckBox Value Change**](../../events/object/on-checkbox-value-change.md)


