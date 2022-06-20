# Overview

![The Is Object 2D Node.](../../../.gitbook/assets/isobject2dnode.png)

The **Is Object 2D Node** returns a **Bool**, depending on whether the input **Object** is *2D* or not. 

# Attributes

![The Is Object 2D Node Attributes.](../../../.gitbook/assets/isobject2dattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**| The **Object** to be checked, if one is not provided in the `Object ID` **Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the **Object** to be checked.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`2D`|**Bool**|Returns *true* if the **Object** is *2D*, *false* otherwise.| 

# See Also

* [**Bool**](../../../objects-and-types/data-types/bool.md)
* [**Is Object 3D**](is-object-3d.md)


