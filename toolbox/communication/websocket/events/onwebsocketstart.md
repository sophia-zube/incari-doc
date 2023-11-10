# Overview

![The On WebSocket Start Node.](../../../../.gitbook/assets/onwebsocketstartnode.png)

The **On WebSocket Start Node** is an **Event Listener Node** notifying that the **WebSocket** connection was successfully established, therefore enabling the user to perform actions on said connection.

**WebSocket Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On WebSocket Start** will not show up in the [**Toolbox**](../../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On WebSocket Start Node Attributes.](../../../../.gitbook/assets/onwebsocketstartatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Dropdown**|The identifying connection name that will be used, which is one that was set up in the [**Project Settings**](../../../modules/project-settings/websocket.md).|


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On WebSocket Error**](onwebsocketerror.md)
* [**On WebSocket Receive**](onwebsocketreceive.md)
* [**On WebSocket Stop**](onwebsocketstop.md)

