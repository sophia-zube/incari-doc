# Overview

![The MQTT Publish Node.](../../../.gitbook/assets/mqttpublish.png)

The **MQTT Publish Node** sends a message to a different location.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Dropdown**|The connection, or signal name, that will be used.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Topic`|**String**|The key in the **MQTT** key/value pair. In the form Topic/name.|
|`Message`|**String**|The value in the **MQTT** key/value pair.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**MQTT Start**](mqttstart.md)
* [**MQTT Subscribe**](mqttsubscribe.md)
* [**MQTT Publish**](mqttpublish.md)

