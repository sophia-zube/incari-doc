# Overview

![The Get Tint Node.](../../../.gitbook/assets/toolbox/incari/object/get-tint.PNG)

**Get Tint** returns the **Color** of the `Tint` **Attribute** of a given **Object**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Object** that you wish to return the `tint` color value of, if one is not provided in the `object ID` **Socket**.|


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** whose `Tint` **Attribute**'s **Color** value should be returned.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Color`|**Color**|An *RGBA* color mode representing the `tint` color value of the target **Object**.|

# See Also
[**SET Tint**](set-tint.md)

# External Links
- [*Tints and Shades*](https://en.wikipedia.org/wiki/Tints_and_shades) on wikipedia.
