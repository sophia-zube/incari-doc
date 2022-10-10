# MQTT

## Introduction

The **MQTT Nodes** provide a means for the user to perform several actions within the _MQTT_ messaging protocol. _MQTT_, or _Message Queuing Telemetry Transport_, allows the communication among devices and is commonly used in _IoT_ applications. To use the **MQTT Nodes** in **Incari**, the user needs to locate the [**MQTT Attributes**](../../../modules/project-settings.md#mqtt) in **Project Settings** and add a `Connection`.

## MQTT Guideline

These are the guidelines for incorporating **MQTT Communication** into a **Project**. It is important to note that an *MQTT* server, either local or remote, has to be already running for **Incari** to connect to it.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **MQTT Communication**.
  * [**On MQTT Topic**](events/onmqtttopic.md) executes when an **MQTT** *Message* (for one of the specified **Topics**) is received.
  * [**MQTT Publish**](mqttpublish.md) sends an **MQTT Message**.
  * [**MQTT Subscribe**](mqttsubscribe.md) starts listening for an **MQTT Topic**. 
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

## Contents

* [**Events**](events/)
  * [**On MQTT Start**](events/onmqttstart.md)
  * [**On MQTT Stop**](events/onmqttstop.md)
  * [**On MQTT Topic**](events/onmqtttopic.md)
* [**MQTT Publish**](mqttpublish.md)
* [**MQTT Start**](mqttstart.md)
* [**MQTT Stop**](mqttstop.md)
* [**MQTT Subscribe**](mqttsubscribe.md)


## External Links

* [_More information on MQTT_](https://en.wikipedia.org/wiki/MQTT) on Wikipedia.
* [_An in-depth explanation and tutorials_](https://mqtt.org/) on MQTT.
* [_An in-depth explanation of Topics_](http://www.steves-internet-guide.com/understanding-mqtt-topics/#:~:text=%20Understanding%20MQTT%20Topics%20%201%20The%20%24SYS,publish%20to%20an%20individual%20topic.%20That...%20More%20)

