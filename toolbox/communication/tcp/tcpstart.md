# Overview

![The TCP Start Node.](../../../.gitbook/assets/tcpstart.png)

The **TCP Start Node** starts a **TCP** connection that has already been set up in [**Project Settings**](../../../modules/project-settings.md#serial).

**TCP Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **TCP Start** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/communication/tcpconnectionsmanager.md) to find out more information.

It is important to note that while the **TCP Start Node** starts a **TCP** connection, it may not completely finish establishing
said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On TCP Start Node**](events/ontcpstart.md) instead. This way, the **Logic** will only execute once the **TCP** connection has definitely been established. 

Again, the user must first use the **TCP Start Node** to open the connection. Separately, the **On TCP Start Node** can be used to execute the desired **Communication Logic**.

![TCP Start and On TCP Start Configuration](../../../.gitbook/assets/tcpstartvsontcpstart.png)

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The TCP Start Node Attributes.](../../../.gitbook/assets/tcpstartatts.png)

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

* [**TCP Stop**](tcpstop.md)
* [**On TCP Start**](events/ontcpstart.md)

