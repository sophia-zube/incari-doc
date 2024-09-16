# Overview

![The On MAVLink Start Node.](../../../../.gitbook/assets/onmavlinkstartnode20241.png)

**On MAVLink Start** is an **Event Listener Node** notifying that the **MAVLink** connection was successfully established, therefore enabling the user to trigger a **Logic Branch** on said connection.

**MAVLink Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On MAVLink Start** will not show up in the [**Toolbox**](../../../overview.md). Please refer to the [**Plugins Editor**](../../../../modules/plugins/README.md) to find out more information.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On MAVLink Start Node Attributes.](../../../../.gitbook/assets/onmavlinkstartatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired *MAVLink* serial port, which refers back to the selections made under *MAVLink* in the [**Project Settings**](../../../../modules/project-settings/mavlink.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On MAVLink Stop**](on-mavlink-stop.md)
  

