# Overview

![The Instantiate Object Node.](../../../.gitbook/assets/instantiateobjectupdatedimage.png)

The **Instantiate Object Node** can be used to copy an **Object**, including all its *children*, or a **Prefab**. 

This **Node** requires a *parent* for the new, copied **Object**. Any **Object** placed in `Parent ID` will automatically be assigned as the *parent*. If the user wishes the copied **Object** to be on the first level in the **Scene** structure, the **Root Object** must be given. 

To learn more about *children* and *parent* **Objects** in the **Scene** structure, as well as the **Root Object**, click [here.](../../../objects-and-types/scene-objects/README.md#structure-in-a-scene)

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
|`Parent`|**ObjectID**|The *parent* to be assigned to the copied **Object** or **Prefab**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Object ID`|**ObjectID**|The ID of the **Object** copy.|

# See Also

* [**Destroy Object**](destroy.md)
* [**Get Root**](get-root.md)