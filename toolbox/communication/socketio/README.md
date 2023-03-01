# Socket.IO

## Introduction

The **Socket.IO** **Nodes** provide a means for the user to perform several actions within the *Socket.IO* communications protocol. *Socket.IO* is related to *WebSocket* and allows for bidirectional communication between servers and web clients using **Socket.IO** events. More information can be found in the official [*Socket.IO* documentation.](https://socket.io/docs/v4/) To use the **Socket.IO Nodes** in **Incari**, the user needs to locate the [**Socket.IO Attributes**](../../../modules/project-settings/socketio.md) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **Socket.IO Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/communication/socketiomanager.md) to find out more information.

## Socket.IO Guideline

These are the guidelines for incorporating **Socket.IO Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **Socket.IO Communication**.
  * [**Socket.IO Send**](socketiosend.md) sends a **Socket.IO** event's `Message` through the established connection. 
  * [**On Socket.IO  Receive**](events/onsocketioreceive.md) executes once a **Socket.IO** event's `Message` is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.



## Contents

* [**Events**](events/)
  * [**On Socket.IO Error**](events/onsocketioerror.md)
  * [**On Socket.IO Receive**](events/onsocketioreceive.md)
  * [**On Socket.IO Start**](events/onsocketiostart.md)
  * [**On Socket.IO Stop**](events/onsocketiounsubscribe.md)
* [**Socket.IO Send**](socketiosend.md)
* [**Socket.IO Start**](socketiostart.md)
* [**Socket.IO Stop**](socketiostop.md)
* [**Socket.IO Subscribe**](socketiosubscribe.md)
* [**Socket.IO Unsubscribe**](socketiounsubscribe.md)
