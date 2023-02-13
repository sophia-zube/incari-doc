# SocketIO

## Introduction

The **SocketIO** **Nodes** provide a means for the user to perform several actions within the *SocketIO* communications protocol. *SocketIO* is related to *WebSocket* and allows for bidirectional communication between a server and client using **SocketIO** events. More information can be found in the official [*SocketIO* documentation.](https://socket.io/docs/v4/) To use the **SocketIO Nodes** in **Incari**, the user needs to locate the [**SocketIO Attributes**](../../../modules/project-settings.md#mqtt) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **SocketIO Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

## SocketIO Guideline

These are the guidelines for incorporating **SocketIO Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **SocketIO Communication**.
  * [**SocketIO Send**](socketiosend.md) sends a **SocketIO** event's `Message` through the established connection. 
  * [**On SocketIO  Receive**](events/onsocketioreceive.md) executes once a **SocketIO** event's `Message` is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.



## Contents

* [**Events**](events/)
  * [**On SocketIO Error**](events/onsocketioerror.md)
  * [**On SocketIO Receive**](events/onsocketioreceive.md)
  * [**On SocketIO Start**](events/onsocketiostart.md)
  * [**On SocketIO Stop**](events/onsocketiounsubscribe.md)
  * [**On SocketIO Subscribe**](events/onsocketiosubscribe.md)
  * [**On SocketIO Unsubscribe**](events/onsocketiounsubscribe.md)
* [**SocketIO Send**](socketiosend.md)
* [**SocketIO Start**](socketiostart.md)
* [**SocketIO Stop**](socketiostop.md)
* [**SocketIO Subscribe**](socketiosubscribe.md)
* [**SocketIO Unsubscribe**](socketiounsubscribe.md)
