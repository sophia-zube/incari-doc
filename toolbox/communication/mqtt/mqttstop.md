# MQTT Stop

## Overview

![The MQTT Stop Node.](../../../.gitbook/assets/mqttstopupdatedimage.png)

The **MQTT Stop Node** stops the **MQTT** connection.

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

## Attributes

![The MQTT Stop Node Attributes.](../../../.gitbook/assets/mqttstopattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The connection, or signal name, that will be used. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**MQTT Start**](mqttstart.md)
* [**MQTT Subscribe**](mqttsubscribe.md)
* [**MQTT Publish**](mqttpublish.md)

