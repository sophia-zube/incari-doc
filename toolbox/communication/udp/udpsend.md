# Overview

![The UDP Send Node.](../../../.gitbook/assets/udpsend.png)

**UDP Send** takes a `Message` and passes it through the currently established **UDP** *connection*. 

Note that if a *connection* has not been established, a new one will be attempted to be made before sending the `Message`. Because of the nature of **UDP**, this is possible and the `Message` will send after the new *connection* is established. 

**UDP Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **UDP Send** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information..

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Attributes

![The UDP Send Node Attributes.](../../../.gitbook/assets/udpsendatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Is Binary`|**Bool**|Can be toggled on or off depending on if the `Message` body is binary or not.|
|`Configuration`|**Drop-Down**|The desired _UDP_ server, which refers back to the selections made under *UDP* in the [**Project Settings**](../../../modules/project-settings.md).| 

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Message`|**String**|The *datagram* to be sent to the endpoint.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also


