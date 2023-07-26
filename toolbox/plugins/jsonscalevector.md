# Overview

![The (JSON) Scale Vector Node.](../../.gitbook/assets/jsonscalevector.png)

The **(JSON) Scale Vector** scales a **Vector3** by the **Float** value given as **Input**. It returns the scaled **Vector3** as well as the norm of the new **Vector3**. 

For example, if a vector of `[3,6,9]` were inputted and the given scaling value were `10`, the resulting `vector` would be `[30,60,90]` and the `norm` would be approximately `112.25`. 


[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input Vector`|**Vector3**|The vector to be scaled.|
|`Scale`|**Float**|The value by which the vector will be scaled.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`norm`|**Float**|The calculated norm of the resulting scaled vector.|
|`vector`|**Vector3**|The resulting scaled vector.|











