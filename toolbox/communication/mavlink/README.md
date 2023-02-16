# MAVLink

## Introduction 

The **MAVLink** **Nodes** provide a means for the user to perform several actions within the *MAVLink* communications protocol. *MAVLink*, or *Micro Air Vehicle Link*, is used for communication with small vehicles, like drones. To use the **MAVLink Nodes** in **Incari**, the user needs to locate the [**MAVLink Attributes**](../../../modules/project-settings/socketio.md) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **MAVLink Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

## MAVLink Guideline

These are the guidelines for incorporating **MAVLink Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **MAVLink Communication**.
  * [**MAVLink Decode**](mavlink-decode.md) decodes any received binary data through the established **MAVLink** connection. 
  * [**On MAVLink Packet Received**](events/on-mavlink-packet-received.md) executes once a **MAVLink** `Message` is received, in the form of binary data.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.



## Contents 

* [**Events**](events/README.md)
  * [**On MAVLink Packet Received**](events/on-mavlink-packet-received.md)
  * [**On MAVLink Start**](events/on-mavlink-start.md)
  * [**On Mavlink Stop**](events/on-mavlink-stop.md)
* [**MAVLink Decode**](mavlink-decode.md)
* [**MAVLink Start**](mavlink-start.md)
* [**MAVLink Stop**](mavlink-stop.md)

## External Links

* What is [MAVLink]?(https://mavlink.io/en/)