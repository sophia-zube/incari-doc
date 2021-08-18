# Overview

![The CAN Send Packet Node.](../../../.gitbook/assets/cansendpacket.png)

The **CAN Send Packet Node** is used to send a data **Packet** along the **CAN** network, once a **CAN** `Message` is selected from the **Dropdown Menu** and a **Signal** has been received.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Message Name`|**Dropdown**|The selected `Message` from uploaded *DBC* file.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**CAN Start**](canstart.md)
* [**CAN Stop**](canstop.md)
