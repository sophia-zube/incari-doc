# Overview

![The On Serial Start Node.](../../../../.gitbook/assets/onserialstartnode.png)

The **On Serial Start Node** is an **Event Listener Node** notifying that the **Serial** connection was successfully established, therefore enabling the user to perform actions on said connection.

**Serial Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings**. Please refer to the [**Plugins Editor**](../../../modules/plugins-editor.md) to find out more information.

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On Serial Start Node Attributes.](../../../../.gitbook/assets/onserialstartattributes.png)


|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The desired **Serial** connection.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On Serial Error**](onserialerror.md)
* [**On Serial Packet Receive**](onserialpacketreceive.md)
* [**On Serial Stop**](onserialstop.md)

