# Overview

![The SocketIO Stop Node.](../../../.gitbook/assets/socketiostop.png)

**SocketIO Stop** stops the **SocketIO** connection.

**SocketIO Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **SocketIO Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

It is important to note that while the **SocketIO Stop Node** stops a **SocketIO** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On SocketIO Stop Node**](events/onsocketiostop.md) instead. This way, the **Logic** will only execute once the **SocketIO** connection has definitely been disconnected from. This way, it is assured that the **Logic** will execute once the connection to the **SocketIO** connection has been terminated.

Again, the user must first use the **SocketIO Stop Node** to close the connection. Separately, the **On SocketIO Stop Node** can be used to execute the desired **Communication Logic**.  

![SocketIO Stop and On SocketIO Stop Configuration.](../../../.gitbook/assets/socketiostopvsonsocketiostop.png).

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The SocketIO Stop Node Attributes.](../../../.gitbook/assets/socketiostopattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _SocketIO_ server, which refers back to the selections made under *SocketIO* in the [**Project Settings**](../../../modules/project-settings/socketio.md).| 

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On SocketIO Stop**](events/onsocketiostop.md)
* [**SocketIO Start**](socketiostart.md)
