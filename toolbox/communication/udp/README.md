# UDP

## Introduction

The **UDP** **Nodes** provide a means for the user to perform several actions within the *UDP* communications protocol. *UDP*, or User Datagram Protocol, is part of the Internet protocol suite and allows for communication to occur with other hosts that are part of an *IP* network. To use the **UDP Nodes** in **Incari**, the user needs to locate the [**UDP Attributes**](../../../modules/project-settings.md#mqtt) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **UDP Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

## UDP Guideline

These are the guidelines for incorporating **UDP Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **UDP Communication**.
  * [**UDP Send**](tcpsend.md) sends a datagram through the established connection to the specified *UDP* endpoint. 
  * [**On TCP Packet Receive**](events/ontcppacketreceive.md) executes once a **UDP** `Message` is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

## Contents

* [**Events**](events/README.md)
  * [**On UDP Error**](events/onudperror.md)
  * [**On UDP Packet Receive**](events/onudppacketreceive.md)
  * [**On UDP Start**](events/onudpstart.md)
  * [**On UDP Stop**](events/onudpstop.md)
* [**UDP Send**](udpsend.md)
* [**UDP Start**](udpstart.md)
* [**UDP Stop**](udpstop.md)