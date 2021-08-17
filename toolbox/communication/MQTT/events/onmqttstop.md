# Overview

![The On MQTT Stop Node.](../../../../.gitbook/assets/onmqttstop.png)

**On MQTT Stop** is an **Event Listener Node** that gives the user a way to perform an action once a **MQTT** connection is disconnected.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Dropdown**|The connection, or signal name, that will be used.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On MQTT Start**](onmqttstart.md)
* [**On MQTT Topic**](onmqtttopic.md)

