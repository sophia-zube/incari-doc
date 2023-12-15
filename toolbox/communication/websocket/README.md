

## Introduction

The **WebSocket** **Nodes** provide a means for the user to perform several actions within the *WebSocket* messaging protocol. *WebSocket* is a communication protocol that provides full-duplex, bidirectional communication channels over a single *TCP* connection. More information can be found [here](https://en.wikipedia.org/wiki/WebSocket). To use the **WebSocket Nodes** in **Incari**, the user needs to locate the [**WebSocket Attributes**](../../../modules/project-settings/websocket.md) in **Project Settings** and add a `Connection`.

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **WebSocket Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

## WebSocket Guideline

These are the guidelines for incorporating **WebSocket Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **WebSocket Communication**.
  * [**On WebSocket Error**](events/onwebsocketerror.md) executes when an error is received.
  * [**On WebSocket Receive**](events/onwebsocketreceive.md) executes when a **WebSocket** message is received. 
  * [**WebSocket Client Send Packet**](websocketsend.md) sends a **WebSocket** message.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

## Contents

* [**Events**](events/README.md)
  * [**On WebSocket Error**](events/onwebsocketerror.md)
  * [**On WebSocket Receive**](events/onwebsocketreceive.md)
  * [**On WebSocket Start**](events/onwebsocketstart.md)
  * [**On WebSocket Stop**](events/onwebsocketstop.md)
* [**WebSocket Client Send**](websocketsend.md)
* [**WebSocket Client Start**](websocketstart.md)
* [**WebSocket Client Stop**](websocketstop.md)