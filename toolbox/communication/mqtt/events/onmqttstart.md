# On MQTT Start

## Overview

![The On MQTT Start Node.](../../../../.gitbook/assets/onmqttstartnode.png)

**On MQTT Start** is an **Event Listener Node** notifying that the **MQTT** connection was successfully established, therefore enabling the user to perform actions on said connection.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

## Attributes

![The On MQTT Start Node Attributes.](../../../../.gitbook/assets/onmqttstartattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The connection, or signal name, that will be used. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**On MQTT Stop**](onmqttstop.md)
* [**On MQTT Topic**](onmqtttopic.md)

