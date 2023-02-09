# SocketIO

## Introduction

The **SocketIO** **Nodes** provide a means for the user to perform several actions within the *SocketIO* communications protocol. *SocketIO* is related to *WebSocket* and allows for bidirectional communication between a server and client using **SocketIO** events. More information can be found in the official [*SocketIO* documentation.](https://socket.io/docs/v4/) To use the **SocketIO Nodes** in **Incari**, the user needs to locate the [**SocketIO Attributes**](../../../modules/project-settings.md#mqtt) in **Project Settings** and add a `Connection`. 

This form of **Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and render the **SocketIO Nodes** unavailable. Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.



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
