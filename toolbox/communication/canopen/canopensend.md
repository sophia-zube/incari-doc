This **Node** has different versions depending on which `Protocol` is selected. This can be either *PDO* or *SDO*. Find in the tabs below the documentation for both versions.

{% tabs %}
{% tab title="PDO" %}
#### Overview

![The CANopen Send: PDO Node.](../../../.gitbook/assets/canopensendpdo.png)

The **CANopen Send Node** is used to send a message once a **CANopen** connection has been selected from the **Drop-down Menu**. Here, the *PDO* `protocol` has been chosen. 

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The CANopen Send: PDO Node Attributes.](../../../.gitbook/assets/canopensendpdoatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The identifying connection name that will be used, which has already been set up in the [**Project Settings**](../../../modules/project-settings/CANopen.md). |
|`Protocol`|**Drop-down**|The desired protocol to use when sending the message. Here, `PDO` has been chosen. After selecting this, `Index` and `Subindex` will provide values. |
|`Is Custom Message`|**Bool**|Can be toggled on or off depending on whether it is a custom message or not. Toggling it on changes the `Index` and `Subindex` into editable input fields allowing values from 0-FFFF for the former and 0-255 for the latter.|
|`Index`|**Drop-down**|The index of the signal. Values depend on which `Protocol` has been selected.|
|`Subindex`|**Drop-down**|The subindex of the signal. Values depend on which `Index` has been selected.|
|`CANopen Type`|**Defined by previous selections**|The value type to be sent which is determined by index and subindex selection.|
|`Message Name`|**String**|A custom name which remains read-only.|
|`Type`|**String**|A message type which remains read-only, unless `Is Custom Message` is set to *true*.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Message`|**Any (Defined by previous selections)**|The value to be sent.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}

{% tab title="SDO" %}
#### Overview

![The CANopen Send: SDO Node.](../../../.gitbook/assets/canopensend.png)

The **CANopen Send Node** is used to send a message once a **CANopen** connection has been selected from the **Drop-down Menu**. Here, the *SDO* `Protocol` has been chosen. 

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The CANopen Send: SDO Node Attributes.](../../../.gitbook/assets/canopensendatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-down**|The identifying connection name that will be used, which has already been set up in the [**Project Settings**](../../../modules/project-settings/CANopen.md). |
|`Protocol`|**Drop-down**|The desired protocol to use when sending the message. Here, `SDO` has been chosen. After selecting this, `Index` and `Subindex` will provide values. |
|`Is Custom Message`|**Bool**|Can be toggled on or off depending on whether it is a custom message or not. Toggling it on changes the `Index` and `Subindex` into editable input fields allowing values from 0-FFFF for the former and 0-255 for the latter.|
|`Index`|**Drop-down**|The index of the signal. Values depend on which `Protocol` has been selected.|
|`Subindex`|**Drop-down**|The subindex of the signal. Values depend on which `Index` has been selected.|
|`CANopen Type`|**Defined by previous selections**|The value type to be sent which is determined by index and subindex selection.|
|`Message Name`|**String**|A custom name which remains read-only.|
|`Type`|**String**|A message type which remains read-only.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Message`|**Any (Defined by previous selections)**|The value to be sent.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}
{% endtabs %}


# See Also

* [**CANopen Start**](canopenstart.md)
* [**CANopen Stop**](canopenstop.md)

# External Links

* Explanation of [*PDO and SDO*](https://community.element14.com/learn/learning-center/the-tech-connection/w/documents/4195/how-does-the-canopen-network-protocol-work).

