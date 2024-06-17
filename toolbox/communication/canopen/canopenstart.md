# Overview

![The CANopen Start Node.](../../../.gitbook/assets/canopenstart.png)

THe **CANopen Start Node** starts communication with a **CANopen** connection that has already been set up in [**Project Settings**](../../../modules/project-settings/CANopen.md).

It is important to note that while the **CANopen Start Node** starts a **CAN** connection, it may not completely finish establishing said connection when the **Node** is executed. This could lead to the **Logic** attached to its **Output Pulse** to not work even though there is technically nothing wrong. In order to avoid this, it is highly suggested to use the [**On CANopen Start Node**](events/oncanopenstart.md) instead. This way, the **Logic** will only execute once the **CANopen** connection has definitely been established.

Again, the user must first use the **CANopen Start Node** to open the connection. Separately, the **On CANopen Start Node** can be used to execute the desired **Communication Logic**.

![CANopen Start and On CANopen Start Configuration.](../../../.gitbook/assets/canopenstartexample.png)

[**Scope**](../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The CANopen Start Node Attributes.](../../../.gitbook/assets/canopenstartatts.png)

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

* [**CANopen Stop**](canopenstop.md)
* [**CANopen Send**](canopensend.md)

