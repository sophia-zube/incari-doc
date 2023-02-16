# Overview

![The MAVLink Decode Node.](../../../.gitbook/assets/mavlinkdecode.png)

**Mavlink Decode** decodes the binary data attributed to the `Message Name` and `Message` identifier **Input** specified. 

**MAVLink Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **MAVLink Decode** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The MAVLink Decode Node Attributes.](../../../.gitbook/assets/mavlinkdecodeatts.png)

|Attribute|Type|Description|
|---|---|---|
| `Message Name` | **Drop-down** | A particular message or command from the selected `Dialect` *XML* file chosen in [**Project Settings**](../../../modules/project-settings/mavlink.md) to be decoded. This defaults to the `MAVLink_Common` `Dialect` in **Project Settings** as it is the only one supported and includes the *standard* `Dialect` and its *minimal* `Dialect`. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Message`| **Binary**| The desired `Message` identifier, that will be compared to the one in the selected `Message Name`. If they are the same, the binary data will be successfully decoded and outputted to their respective outputs which appear when a `Message Name` has been selected. If not, the **Node** fails to fire correctly.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On MAVLink Packet Received**](events/on-mavlink-packet-received.md)
