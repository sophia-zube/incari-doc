# HTTP Server Stop

## Overview

![The HTTP Server Stop Node.](../../../.gitbook/assets/httpserverstopnode.png)

The **HTTP Server Stop Node** terminates the connection with an _HTTP_ server.

*Scope*: **Project**, **Scene**

## Attributes

![The HTTP Server Stop Node Attributes.](../../../.gitbook/assets/httpserverstopattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The desired _HTTP_ server. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**HTTP Server Start**](httpserverstart.md)

