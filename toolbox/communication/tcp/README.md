# TCP

## Introduction

The **TCP** **Nodes** provide a means for the user to perform several actions within the *TCP* communications protocol. *TCP*, or Transmission Control Protocol, is part of the Internet protocol suite and allows for bidirectional communication between a server and a client. To use the **TCP Nodes** in **Incari**, the user needs to locate the [**TCP Attributes**](../../../modules/project-settings.md#mqtt) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **TCP Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

## TCP Guideline

These are the guidelines for incorporating **TCP Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **TCP Communication**.
  * [**TCP Send**](tcpsend.md) sends a `Message` through the established connection to the *TCP* endpoint. 
  * [**On TCP Packet Receive**](events/ontcppacketreceive.md) executes once a **TCP** `Message` is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.


## Contents

* [**Events**](events/README.md)
  * [**On TCP Error**](events/ontcperror.md)
  * [**On TCP Packet Receive**](events/ontcppacketreceive.md)
  * [**On TCP Start**](events/ontcpstart.md)
  * [**On TCP Stop**](events/ontcpstop.md)
* [**TCP Send**](tcpsend.md)
* [**TCP Start**](tcpstart.md)
* [**TCP Stop**](tcpstop.md)