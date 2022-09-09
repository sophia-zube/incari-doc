# MQTT Stop

## Overview

![The MQTT Stop Node.](../../../.gitbook/assets/mqttstopnode.png)

The **MQTT Stop Node** stops the **MQTT** connection.

It is important to note that while the **MQTT Stop Node** stops a **MQTT** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On MQTT Stop Node**](events/onmqttstop.md) instead. This way, the **Logic** will only execute once the **MQTT** connection has definitely been disconnected from. 

Again, the user must first use the **MQTT Stop Node** to close the connection. Separately, the **On MQTT Stop Node** can be used to execute the desired **Communication Logic**. 

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

