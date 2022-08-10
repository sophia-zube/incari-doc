# MQTT Publish

## Overview

![The MQTT Publish Node.](../../../.gitbook/assets/mqttpublishnode.png)

The **MQTT Publish Node** sends a message to a different location.

[**Scope**](../overview.md#scopes):
*  **Project**, **Scene**

## Attributes

![The MQTT Publish Node Attributes.](../../../.gitbook/assets/mqttpublishattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The connection, or signal name, that will be used. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Topic` | **String** | The key in the **MQTT** key/value pair, in the form _Topic/name_. |
| `Message` | **String** | The value in the **MQTT** key/value pair. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**MQTT Start**](mqttstart.md)
* [**MQTT Stop**](mqttstop.md)
* [**MQTT Subscribe**](mqttsubscribe.md)

## External Links

* [_An in-depth explanation of Topics_](http://www.steves-internet-guide.com/understanding-mqtt-topics/#:~:text=%20Understanding%20MQTT%20Topics%20%201%20The%20%24SYS,publish%20to%20an%20individual%20topic.%20That...%20More%20)

