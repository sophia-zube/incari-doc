# Overview

![The Serial Start Node.](../../../.gitbook/assets/serialstartupdatedimage.png)

The **Serial Start Node** starts a **Serial** connection that has already been set up in [**Project Settings**](../../../modules/project-settings.md#serial).

**Serial Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **Serial Start** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins-editor.md) to find out more information.

It is important to note that while the **Serial Start Node** starts a **Serial** connection, it may not completely finish establishing
said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On Serial Start Node**](events/onserialstart.md) instead. This way, the **Logic** will only execute once the **CAN** connection has definitely been established. 

Again, the user must first use the **Serial Start Node** to open the connection. Separately, the **On Serial Start Node** can be used to execute the desired **Communication Logic**.

![Serial Start and On Serial Start Configuration](../../../.gitbook/assets/serialstartvsonserialstart.png)

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The Serial Start Node Attributes.](../../../.gitbook/assets/serialstartattributes.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The desired **Serial** connection.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Serial Send Packet**](serialsendpacket.md)
* [**Serial Stop**](serialstop.md)

