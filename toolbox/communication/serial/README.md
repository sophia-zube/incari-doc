# Introduction

The **Serial** **Nodes** allow the user to connect to serial devices -- like GPS devices -- via USB or serial ports using *Serial* *Communication*. *Serial* *Communication* sends single bits of data at a time, sequentially, through a communication channel/bus. To use the **Serial** **Nodes** in **Incari**, the user first needs to locate the [**Serial Attributes**](../../../modules/project-settings.md#serial) in **Project** **Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **Serial Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins-editor.md) to find out more information.

## Serial Guideline

These are the guidelines for incorporating **Serial Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **Serial Communication**.
  * [**On Serial Error**](events/onserialerror.md) executes when an error is received.
  * [**On Serial Packet Received**](events/onserialpacketreceive.md) executes when a **Serial** data **Packet** is received. 
  * [**Serial Send Packet**](serialsendpacket.md) sends a **Serial** data **Packet**.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.



# Contents

* [**Events**](events/)
  * [**On Serial Error**](events/onserialerror.md)
  * [**On Serial Packet Receive**](events/onserialpacketreceive.md)
  * [**On Serial Start**](events/onserialstart.md)
  * [**On Serial Stop**](events/onserialstop.md)
* [**Serial Send Packet**](serialsendpacket.md)
* [**Serial Start**](serialstart.md)
* [**Serial Stop**](serialstop.md)


# External Links

* [*Serial Communication*](https://en.wikipedia.org/wiki/Serial_communication) on Wikipedia.
* [*Learn about Serial Communication*](https://learn.sparkfun.com/tutorials/serial-communication/all) on SparkFun. 
