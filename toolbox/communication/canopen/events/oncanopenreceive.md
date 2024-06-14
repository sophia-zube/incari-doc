# Overview

![The On CANopen Receive Node.](../../../../.gitbook/assets/oncanopenreceive.png)

**On CANopen Receive Node** is an **Event Listener Node** allowing the user to perform an action once a **CANopen** `Configuration` is selected from the **Drop-down Menu**.

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On CANopen Receive Node Attributes.](../../../../.gitbook/assets/oncanopenreceiveatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The identifying connection name that will be used, which has already been set up in the [**Project Settings**](../../../modules/project-settings/CANopen.md).|
|`Index`|**Drop-down**|The index of the signal. Values depend on which `Protocol` has been selected.|
|`Subindex`|**Drop-down**|The subindex of the signal. Values depend on which `Index` has been selected.|
|`Value Type`|**Defined by previous selections**|The value type to be sent which is determined by index and subindex selection.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Value`|**Any**|The received value.|

# See Also

* [**On CANopen Start**](oncanopenstart.md)
* [**On CANopen Stop**](oncanopenstop.md)

