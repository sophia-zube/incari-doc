# CAN

## Introduction

The **CAN Nodes** provide a means for the user to perform several actions within the _CAN_ messaging protocol. _CAN_, or _Controller Area Network_, allows for communication among different devices, such as different electronic parts of a vehicle. To use the **CAN Nodes** in **Incari**, the user needs to locate the [**CAN Attributes**](../../../modules/project-settings.md#can) in **Project Settings** and upload a _DBC_ file.

## CAN Guideline

These are the guidelines for incorporating **CAN Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **CAN Communication**.
  * [**CAN Send Packet**](cansendpacket.md) sends a **CAN** data **Packet** when a signal is received. 
  * [**On CAN Packet Received**](events/oncanpacketreceived.md) executes once a **Packet** is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.


## Contents

* [**CAN Send Packet**](cansendpacket.md)
* [**CAN Start**](canstart.md)
* [**CAN Stop**](canstop.md)
* [**Events**](events/)
  * [**On CAN Packet Received**](events/oncanpacketreceived.md)
  * [**On Can Start**](events/oncanstart.md)
  * [**On Can Stop**](events/oncanstop.md)

## External Links

* [_More information on CAN_](https://en.wikipedia.org/wiki/CAN_bus) on Wikipedia.

