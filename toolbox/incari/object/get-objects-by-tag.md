# Overview

![The Get Objects By Tag Node.](../../../.gitbook/assets/getobjectsbytagnode.png)

The **Get Objects By Tag Nodes** returns an **Array** of all **Objects**, specifically their **IDs**, which are associated with the given *tag*.

![The Get Objects By Tag Node Attributes.](../../../.gitbook/assets/getobjectsbytagattributes.png)

# Attributes

|Attribute|Type|Description|
|---|---|---|
## Object

|Attribute|Type|Description|
|---|---|---|
|`Object`| **ObjectID** |An **Object** with the associated *tag*, if one is not provided in the **Input Socket**.|

## Input

|Attribute|Type|Description|
|---|---|---|
| `Tag` | **String** |The *tag* of interest, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|An **Object** with the associated *tag*.|
|`Tag`|**String**|The *tag* of interest.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Object IDs`|An **Array** of all the **Object IDs** with the associated *tag*.| 

# See Also

* [**Add Tag**](add-tag.md)
* [**Remove Tag**](remove-tag.md)



