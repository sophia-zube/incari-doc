# Overview

![The Set Scale Node.](../../../.gitbook/assets/toolbox/incari/object/set-scale.PNG)

**Set Scale** sets the value of a given **Object**'s `Scale` **Attribute**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The ID of the **Object** that you would like to set the `Scale` value of if one is not provided in the `Object ID` **Socket**.|
|`Scale`|**Vector3**|The desired `Scale` value of the **Object** if one is not provided in the `Scale` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that you would like to set the `Scale` value of.|
|`Scale`|**Vector3**|The desired `Scale` value of the **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also
- [**Get Scale**](get-scale.md)

# External Links
- [*Scaling*](https://en.wikipedia.org/wiki/Scaling_(geometry)) in geometry.
