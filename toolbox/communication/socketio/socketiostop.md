# Overview

![The Socket.IO Stop Node.](../../../.gitbook/assets/socketiostopnode20241.png)

**Socket.IO Stop** stops the currently opened **Socket.IO** connection.

**Socket.IO Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **Socket.IO Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/communication/socketiomanager.md) to find out more information.

It is important to note that while the **Socket.IO Stop Node** stops a **Socket.IO** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On Socket.IO Stop Node**](events/onsocketiostop.md) instead. This way, the **Logic** will only execute once the **Socket.IO** connection has definitely been disconnected from. This way, it is assured that the **Logic** will execute once the connection to the **Socket.IO** connection has been terminated.

Again, the user must first use the **Socket.IO Stop Node** to close the connection. Separately, the **On Socket.IO Stop Node** can be used to execute the desired **Communication Logic**.  

![Socket.IO Stop and On Socket.IO Stop Configuration.](../../../.gitbook/assets/socketiostopexamplereal.png)

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The Socket.IO Stop Node Attributes.](../../../.gitbook/assets/socketiostopattsreal.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _Socket.IO_ server, which refers back to the selections made under *Socket.IO* in the [**Project Settings**](../../../modules/project-settings/socketio.md).| 

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On Socket.IO Stop**](events/onsocketiostop.md)
* [**Socket.IO Start**](socketiostart.md)
