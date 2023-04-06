# Overview

![The UDP Stop Node.](../../../.gitbook/assets/udpstop.png)

**UDP Stop** stops the **UDP** connection, which was previously established with [**UDP Start**](udpstart.md).

**UDP Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **UDP Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

It is important to note that while the **UDP Stop Node** stops a **UDP** connection, it may not completely finish disconnecting from said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On UDP Stop Node**](events/onudpstop.md) instead. This way, the **Logic** will only execute once the **UDP** connection has definitely been disconnected from. This way, it is assured that the **Logic** will execute once the connection to the **UDP** connection has been terminated.

Again, the user must first use the **UDP Stop Node** to close the connection. Separately, the **On UDP Stop Node** can be used to execute the desired **Communication Logic**.  

![UDP Stop and On UDP Stop Configuration.](../../../.gitbook/assets/udpstopvsonudpstop.png)

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The UDP Stop Node Attributes.](../../../.gitbook/assets/udpstopatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _UDP_ server, which refers back to the selections made under *UDP* in the [**Project Settings**](../../../modules/project-settings/udp-connection.md).| 

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

