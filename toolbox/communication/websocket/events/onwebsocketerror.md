# Overview

![The On WebSocket Error Node.](../../../../.gitbook/assets/onwebsocketerrornode20241.png)

The **On WebSocket Error Node** is an **Event Listener Node** that is triggered if the specified *WebSocket* connection encounters an error during any action and returns the error `Message`.

**WebSocket Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On WebSocket Error** will not show up in the [**Toolbox**](../../../overview.md). Please refer to the [**Plugins Editor**](../../../../modules/plugins/README.md) to find out more information.


[**Scope**](../../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On WebSocket Error Node Attributes](../../../../.gitbook/assets/onwebsocketerroratts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Dropdown**|The identifying connection name that will be used, which is one that was set up in the [**Project Settings**](../../../../modules/project-settings/websocket.md).|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Message`|**String**|The returned error `Message`.|

# See Also

* [**On WebSocket Receive**](onwebsocketreceive.md)
* [**On WebSocket Start**](onwebsocketstart.md)
* [**On WebSocket Stop**](onwebsocketstop.md)


