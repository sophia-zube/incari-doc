# Overview

![The Instantiate Object Node.](../../../.gitbook/assets/instantiatenode.png)

The **Instantiate Object Node** can be used to copy an **Object**, including all its *children*, or a **Prefab**. 

# Attributes

![The Instantiate Object Node Attributes.](../../../.gitbook/assets/instantiateobjectattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Object** or **Prefab** to be copied, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** or **Prefab** to be copied.|
|`Parent`|**ObjectID**|The *parent* of the **Object** or **Prefab** to be copied.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Object ID`|**ObjectID**|The ID of the **Object** copy.|

# See Also

* [**Destroy**](destroy.md)