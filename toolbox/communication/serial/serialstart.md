# Overview

![The Serial Start Node.](../../../.gitbook/assets/serialstartnode.png)

The **Serial Start Node** starts a **Serial** connection that has already been set up in [**Project Settings**](../../../modules/project-settings.md#serial).

It is important to note that while the **Serial Start Node** starts a **Serial** connection, it may not completely finish establishing
said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** 
to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use 
the [**On Serial Start Node**](events/onserialstart.md) instead. This way, the **Logic** will only execute once the **CAN** connection has definitely been established. 

Again, the user must first use the **Serial Start Node** to open the connection. Separately, the **On Serial Start Node** can be used to execute the desired **Communication Logic**.

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

