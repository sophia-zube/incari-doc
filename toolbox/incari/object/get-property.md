# Overview

![The Get Property Node.](../../../.gitbook/assets/getproperty.png)

The **Get Property Node** returns the value of a single *CSS* property at runtime using the **Logic**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Get Property Node Attributes.](../../../.gitbook/assets/getpropertyattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Name`|**String**|The name of the property to be returned, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** whose property will be returned.|
|`Name`|**String**|The name of the property whose value will be returned.|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Value`|**String**|The value of the property to be returned.|


# See Also

* [**Set Property**](set-property.md)