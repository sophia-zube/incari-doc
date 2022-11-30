# Overview

![The Get Name Node.](../../../.gitbook/assets/getnameupdatedimage.png)

The **Get Name Node** returns the name of an **Object** when its **Object ID** is provided.

# Attributes

![The Get Name Node Attributes.](../../../.gitbook/assets/getnamenodeattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Object** whose name will be returned, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** whose name will be returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Object Name`|**String**|Returns the name of the specified **Object**.|
