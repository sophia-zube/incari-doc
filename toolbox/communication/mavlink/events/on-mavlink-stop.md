# Overview

![The On MAVLink Stop Node.](../../../../.gitbook/assets/onmavlinkstop.png)

**On MAVLink Stop**is an **Event Listener Node** allowing the user to trigger a **Logic Branch** once a connection to an **MAVLink** serial port has been terminated.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On MAVLink Stop Node Attributes.](../../../../.gitbook/assets/onmavlinkstopatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired *MAVLink* serial port, which refers back to the selections made under *MAVLink* in the [**Project Settings**](../../../../modules/project-settings/mavlink.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On MAVLink Start**](on-mavlink-start.md)

