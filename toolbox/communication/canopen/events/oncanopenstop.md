# Overview

![The On CANopen Stop Node.]()

The **On CANopen Stop Node** is an **Event Listener Node** allowing the user to perform an action once a **CANopen** process has ended..

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On CANopen Stop Node Attributes.]()

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The identifying connection name that will be used, which has already been set up in the [Project Settings](../../../modules/project-settings/CANopen.md).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On CANopen Receive**](oncanopenreceive.md)
* [**On CANopen Start**](oncanopenstart.md)

