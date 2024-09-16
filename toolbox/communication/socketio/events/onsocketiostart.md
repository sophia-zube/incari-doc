# Overview

![The On Socket.IO Start Node.](../../../../.gitbook/assets/onsocketiostartnode20241.png)

**On Socket.IO Start** is an **Event Listener Node** notifying that the **Socket.IO** connection was successfully established, therefore enabling the user to trigger a **Logic Branch** on said connection to the *Socket.IO* server.

**Socket.IO Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On Socket.IO Start** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../../modules/plugins/communication/socketiomanager.md) to find out more information.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On Socket.IO Start Node Attributes.](../../../../.gitbook/assets/onsocketiostartattsreal.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _Socket.IO_ server, which refers back to the selections made under *Socket.IO* in the [**Project Settings**](../../../../modules/project-settings/socketio.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On Socket.IO Stop**](onsocketiostop.md)



