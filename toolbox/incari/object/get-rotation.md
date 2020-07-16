# Overview

![The Get Rotation Node.](../../../.gitbook/assets/toolbox/incari/object/get-rotation.PNG)

| Input | Output |
| :--- | :--- |
| Object ID | Rotation |

**Get Rotation** returns the *rotation* of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|Int|The ID of the **Object** whose *rotation* is to be determined.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scale`| 3D vector | A 3 dimensional vector that contains *rotation* in the x, y and z directions.

# See Also
[**Get Scale**](get-scale.md)
[**Get Position**](get-position.md)

# External Links
- [*Rotation*](https://en.wikipedia.org/wiki/Rotation_matrix) on wikipedia
- [*Rotation*](https://www.khanacademy.org/computing/computer-programming/programming-games-visualizations/programming-3d-shapes/a/rotating-3d-shapes) on Khan Academy

