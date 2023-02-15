# Overview

![The On MAVlink Packet Received Node.](../../../../.gitbook/assets/onmavlinkpacketreceive.png)

**On MAVLink Packet Received**  is an **Event Listener Node** allowing the user to trigger a **Logic Branch** when *MAVLink* data  is received and returned in the form of a binary `Message`. This message need to be decoded to access the data, which is done with [**MAVLink Decode**](../mavlink-decode.md).

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On MAVLink Packet Received Node Attributes.](../../../../.gitbook/assets/onmavlinkpacketreceivedatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired *MAVLink* serial port, which refers back to the selections made under *MAVLink* in the [**Project Settings**](../../../modules/project-settings.md).| 


# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Message`|**Binary**|The returned `Message`.|


# See Also

* [**MAVLink Decode**](../mavlink-decode.md)