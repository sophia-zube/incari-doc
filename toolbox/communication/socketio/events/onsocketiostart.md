# Overview

![The On SocketIO Start Node.](../../../../.gitbook/assets/onsocketiostart.png)

**On SocketIO Start** is an **Event Listener Node** notifying that the **SocketIO** connection was successfully established, therefore enabling the user to perform actions on said connection to the *SocketIO* server.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On SocketIO Start Node Attributes.](../../../../.gitbook/assets/socketiostartattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _SocketIO_ server, which refers back to the selections made under *SocketIO* in the [**Project Settings**](../../../modules/project-settings.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On SocketIO Stop**](onsocketiostop.md)



