# Overview

![The Get Text Color Node.](../../../.gitbook/assets/gettextcolor.png)

The **Set Text Color Node** gets, or returns, the **Color** of a **Text Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Get Text Color Node Attributes.](../../../.gitbook/assets/gettextcolorattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Text** **Object** whose **Color** will be returned, if one is not provided in the `Object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Text** **Object** whose **Color** will be returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Color`|**Color**|The returned **Color** value.|

# See Also

* [**Set Text Color**](set-text-color.md)

