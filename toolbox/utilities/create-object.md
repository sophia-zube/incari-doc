# Overview

![The Create Object Node.](../../.gitbook/assets/node-create-object.png)

The **Create Object** **Node** creates [**Scene Objects**](../../getting-started/scene-objects/README.md) of a chosen **Object Type**.

# Attributes

## Object Type

|Attribute|Type|Description|
|---|---|---|
| `Object Type` | **Drop-down** | The **Object Type** of the newly created **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Parent ID` | **ObjectID** | |
| `is 2D` | **Bool** | Wheter the newly created **Object** will be *2D* or *3D*. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Object ID` | **ObjectID** | The unique generated **ObjectID** of the newly created **Object**. |
| `Success` | **Bool** | Wheter the operation of creating the desired **Object** was successful or not. |

# See Also

* [**Scene Objects**](../../getting-started/scene-objects/README.md)



