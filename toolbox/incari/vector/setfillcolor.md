# Overview

![The Set FillColor Node.](../../../.gitbook/assets/setfillcolor.png)

The **Set FillColor Node** sets the **FillColor**, visualized as the inside color, of a **Vector Object** created in the **Scene Outliner Module** under *Vector*. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **ObjectID** | The target **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | The ID of the target **Object**. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`FillColor`|**Color**| The **FillColor** of the target **Object**.|

# See Also

* [**Get FillColor**](getfillcolor.md)

