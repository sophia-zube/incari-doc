# Overview

![The Console Node.](../../../.gitbook/assets/node-console.png)

The **Console** **Node** is used for showing a value of any **Data Type** on the console.

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | **Data Type** of the `Input` and `Output` **Sockets**. |
| `Type` | **Drop-down** | Type of the message that will appear on the console. |
| `Value` | _Defined in the `Data Type` **Attribute**_ | Default value, if none is received in the `Input` **Socket**. |


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Input` |  _Defined in the `Data Type` **Attribute**_ | Value that will be shown on the console.  |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Output` |  _Defined in the `Data Type` **Attribute**_ | Value that was shown on the console. |

# See Also

* [**Clear Console**](clear-console.md)

