# Overview

![The Get BackgroundColor Node.](../../../.gitbook/assets/getbackgroundcolor.png)

The **Get BackgroundColor Node** returns the **BackgroundColor** of the target **Vector Object**. For example, this could be the **BackgroundColor** of an **Ellipse**, which can be created in the **Scene Outliner Module** under *Vector*. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Object` | **Object ID** | The target **Object**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **Object ID** | The ID of the target **Object**. |


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`BackgroundColor`|**Color**| The **BackgroundColor** of the target **Object**.|

