# Overview

![The Get Objects By Tag Node.](../../../.gitbook/assets/getobjectsbytagnode.png)

The **Get Objects By Tag Nodes** returns an **Array** of all **Objects**, specifically their **IDs**, which are associated with the given *tag* and fall under a given *parent* **Object**. If an **Object** has no explicit *parent* given by the user, the *parent* defaults to the **Root Object**, thus requiring the [**Get Root Node**](get-root.md). 

To learn more about the **Root Object** and **Scene** structure, click [here.](../../../objects-and-types/scene-objects/README.md#structure-in-a-scene) 

![The Get Objects By Tag Node Attributes.](../../../.gitbook/assets/getobjectsbytagattributes.png)

# Attributes

|Attribute|Type|Description|
|---|---|---|
## Object

|Attribute|Type|Description|
|---|---|---|
|`Object`| **ObjectID** |The *parent* **Object**, or upper bound, if one is not provided in the **Input Socket**.|

## Input

|Attribute|Type|Description|
|---|---|---|
| `Tag` | **String** |The *tag* of interest, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|An *parent* **Object**, or upper bound.|
|`Tag`|**String**|The *tag* of interest.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Object IDs`|An **Array** of all the **Object IDs** with the associated *tag*.| 

# See Also

* [**Add Tag**](add-tag.md)
* [**Remove Tag**](remove-tag.md)



