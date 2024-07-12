# Overview

![The Set Language Node.](../../.gitbook/assets/setlanguagenode.png)

The **Set Language Node** sets the language being used on the execution of the **Node**. It can be selected in its **Attributes** or added in the **Input Socket**.

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**. 

# Attributes

![The Set Language Node Attribute.](../../.gitbook/assets/setlanguageatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Language`|**String**|The language to be set during the execution of the **Node**, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Language`|**String**|The language to be set during the execution of the **Node**.|
|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get Language**](getlanguage.md)

