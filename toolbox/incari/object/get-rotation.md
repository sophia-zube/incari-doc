# Overview

![The Get Rotation Node.](../../../.gitbook/assets/toolbox/incari/object/get-rotation.PNG)

**Get Rotation** returns the *rotation* of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object** that you wish to return the `rotation` of, if one is not provided in the `Object ID` **Socket**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object** whose *rotation* value you wish to return.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Rotation`|**Vector3** | A 3-dimensional vector that contains *Euler rotation* on the x, y, and z axes of the target **Object**.

# See Also
- [**Get Scale**](get-scale.md)
- [**Get Position**](get-position.md)
- [**Set Rotation**](set-rotation.md)

# External Links
- [*Rotation*](https://en.wikipedia.org/wiki/Euler_angles) on wikipedia
