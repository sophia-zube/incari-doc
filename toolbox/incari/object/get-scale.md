# Overview

![The Get Scale Node.](../../../.gitbook/assets/toolbox/incari/object/get-scale.PNG)

| Input | Output |
| :--- | :--- |
| Object ID | Scale |


**Get Scale** returns the *scale* of an **Object** in a **Scene**. The **Object ID** is given as input to the **Node**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|Int|The ID of the **Object** whose *scale* is to be determined.

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Scale`| 3D vector | A 3 dimensional vector that contains scaling in the x, y and z directions.

# See Also
- [**Get Rotation**](get-rotation.md) 
- [**Get Position**](get-position.md)

# External Links
- [*Scaling*](https://en.wikipedia.org/wiki/Scaling_(geometry)) in geometry.