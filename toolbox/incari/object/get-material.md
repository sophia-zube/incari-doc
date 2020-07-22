# Overview

![The Get Material Node.](../../../.gitbook/assets/toolbox/incari/object/get-material.PNG)

**Get Material** returns the **Material** assert applied to a **Mesh** of an **Object**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** whose `Material` assert you would like to return, if one is not provided in the `object ID` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object`|**ObjectID**|The ID of the target **Object** whose `material` assert you seek to return.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Material`|**MaterialID**|`Material` assert of the target **Object**.|

# See Also
- [**Set Material**](set-material.md)
  
# External Links
- [*Materials*](https://docs.unrealengine.com/en-US/Engine/Rendering/Materials/index.html)
