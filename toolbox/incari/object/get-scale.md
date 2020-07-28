# Overview

![The Get Scale Node.](../../../.gitbook/assets/toolbox/incari/object/get-scale.PNG)

**Get Scale** returns the *scale* of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** that you wish to return the `scale` of if one is not provided in the `Object ID` **Socket**

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object** whose *scale* value you wish to return.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scale`| **Vector3** | A 3 dimensional vector that contains scaling in the x, y and z directions of the target **Object**.

# See Also
- [**Get Rotation**](get-rotation.md) 
- [**Get Position**](get-position.md)

# External Links
- [*Scaling*](https://en.wikipedia.org/wiki/Scaling_(geometry)) in geometry.
