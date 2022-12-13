# Overview

![The Get All Cameras Node.](../../../.gitbook/assets/node-get-all-cameras.png)

The **Get All Cameras** **Node** outputs an **Array** containing the **Object IDs** of all available **Cameras** in the **Scene**.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Available Cameras` | **Array** | **Array** containing the **Object IDs** of all available **Cameras**. |

# See Also

* [**Camera**](../../../objects-and-types/scene-objects/camera.md)

