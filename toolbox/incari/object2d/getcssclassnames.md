# Overview

![The Get CSS Class Names Node.](../../../.gitbook/assets/getcssclassnames.png)

**Get CSS Class Names Node** returns all the CSS class names of the gien **Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** for which the user wishes to have all *CSS* class names.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Class Names`|**String**|The resulting **String** that contains all *CSS* class names of the **Object**.|


