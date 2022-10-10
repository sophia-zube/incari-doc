# Overview

![The On Serial Stop Node.](../../../../.gitbook/assets/onserialstopnode.png)

The **On Serial Stop Node** is an **Event Listener Node** that gives the user a way to perform an action once a **Serial** connection has been terminated.

**Serial Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On Serial Stop** will not show up in the **Toolbox**. Please refer to the [**Plugins Editor**](../../../modules/plugins-editor.md) to find out more information.

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On Serial Stop Node Attributes.](../../../../.gitbook/assets/onserialstopattributes.png)

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
* [**On Serial Start**](onserialstart.md)

