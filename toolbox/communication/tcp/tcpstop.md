# Overview

![The TCP Stop Node.](../../../.gitbook/assets/tcpstopnode20241.png)

**TCP Stop** stops the currently opened **TCP** connection.

**TCP Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **TCP Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/communication/tcpconnectionsmanager.md) to find out more information.

It is important to note that while the **TCP Stop Node** stops a **TCP** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On TCP Stop Node**](events/ontcpstop.md) instead. This way, the **Logic** will only execute once the **TCP** connection has definitely been disconnected from. This way, it is assured that the **Logic** will execute once the connection to the **TCP** connection has been terminated.

Again, the user must first use the **TCP Stop Node** to close the connection. Separately, the **On TCP Stop Node** can be used to execute the desired **Communication Logic**.  

![TCP Stop and On TCP Stop Configuration.](../../../.gitbook/assets/tcpstopvsontcpstop.png)

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The TCP Stop Node Attributes.](../../../.gitbook/assets/tcpstopatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _TCP_ server, which refers back to the selections made under *TCP* in the [**Project Settings**](../../../modules/project-settings/tcp-connection.md).| 

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**TCP Start**](tcpstart.md)
* [**On TCP Stop**](events/ontcpstop.md)