# Overview

![The Set Material Node.](../../../.gitbook/assets/toolbox/incari/object/set-material.PNG)

**Set Material** applies a material asset to an **Object** **Mesh**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The **Object** which the `material` is to be applied to, if one is not provided in the `object ID` **Socket**.|
|`Default Material`|**MaterialID**|The default value of the `Material` **Socket**, if no value is provided.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object`|**ObjectID**|The ID of the **Object** you would like to apply a `Material` asset.|
|`Material`|**MaterialID**|The `Material` to be applied to the **Object** **Mesh**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also
- [**Get Material**](get-material.md)
  
# External Links
- [*Materials*](https://docs.unrealengine.com/en-US/Engine/Rendering/Materials/index.html)
