# Overview

![The WebSocket Client Stop Node.](../../../.gitbook/assets/websocketclientstop.png)

The **WebSocket Client Stop Node** halts communication with a **WebSocket** connection.

**WebSocket Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **WebSocket Client Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

It is important to note that while the **WebSocket Client Stop Node** stops a **WebSocket** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On WebSocket Stop Node**](events/onwebsocketstop.md) instead. This way, it is assured that the **Logic** will execute once the connection to the **WebSocket** connection has been terminated.

Again, the user must first use the **WebSocket Client Stop Node** to close the connection. Separately, the **On WebSocket Stop Node** can be used to execute the desired **Communication Logic**. 


![WebSocket Client Stop and On WebSocket Stop Configuration.](../../../.gitbook/assets/websocketstoponstopexample.png)



[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The WebSocket Client Stop Node Attributes.](../../../.gitbook/assets/websocketclientstopatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Dropdown**|The identifying connection name that will be used, which is one that was set up in the [**Project Settings**](../../../modules/project-settings/websocket.md).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On WebSocket Stop**](events/onwebsocketstop.md)
* [**WebSocket Client Send**](websocketsend.md)

