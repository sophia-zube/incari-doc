# Overview

![The On Socket.IO Receive Node.](../../../../.gitbook/assets/onsocketioreceivenode20241.png)

**On Socket.IO Receive** is an **Event Listener Node** that executes and triggers a **Logic Branch** when data of a **Socket.IO** event is received and returns its `Message`, name, and `Namespace`.

**Socket.IO Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On Socket.IO Receive** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../../modules/plugins/communication/socketiomanager.md) to find out more information.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On Socket.IO Receive Node Attributes.](../../../../.gitbook/assets/onsocketioreceiveattsreal.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _Socket.IO_ server, which refers back to the selections made under *Socket.IO* in the [**Project Settings**](../../../../modules/project-settings/socketio.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Namespace`|**String**| An identifying name that is *parent* to an event or events in the **Socket.IO** protocol. The default is simply `/`.|
|`Trigger Name`|**String**| The name of the event.|
|`Message`|**String**| The returned `Message`.|




