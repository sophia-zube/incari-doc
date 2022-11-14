# On MQTT Topic

## Overview

![The On MQTT Topic Node.](../../../../.gitbook/assets/onmqtttopicupdatedimage.png)

**On MQTT Topic** is an **Event Listener Node** that executes when an **MQTT** *Message* (only for the specificed `Topics`) is received. `Topics` are *strings* that act as filters for *Messages* and are hierarchical, meaning there are different levels. Remember, they are case sensitive. 

In order to use this **Node**, the user must have already subscribed to the specified `Topics` with the [**MQTT Subscribe Node**](../mqttsubscribe.md).

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

## Attributes

![The On MQTT Topic Node Attributes.](../../../../.gitbook/assets/onmqtttopicattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The connection, or signal name, that will be used. |
| `Topic` | **User Input** | The key in the **MQTT** key/value pair. |

## Example

![On MQTT Topic Example.](../../../../.gitbook/assets/onmqtttopicexample.png)

The above image shows what happens when an **MQTT** connection has been made in the **Project Settings**. The connection's name will appear under `Configuration`. One or more `Topic Names` can be added, which appear as **Output Pulses** on the **Node**. It is possible to specify if they are binary or not. Each of these `Topics` have a corresponding `Body` **String**, which is the value in the **MQTT** key/value pair. 

## See Also

* [**On MQTT Start**](onmqttstart.md)
* [**On MQTT Stop**](onmqttstop.md)

## External Links

* [_An in-depth explanation of Topics_](http://www.steves-internet-guide.com/understanding-mqtt-topics/#:~:text=%20Understanding%20MQTT%20Topics%20%201%20The%20%24SYS,publish%20to%20an%20individual%20topic.%20That...%20More%20)

