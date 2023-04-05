# Overview

![The On UDP Stop Node.](../../../../.gitbook/assets/onudpstop.png)

**On UDP Stop** is an **Event Listener Node** allowing the user to trigger a **Logic Branch** once a connection to an **UDP** server has been terminated.

**UDP Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On UDP Stop** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information..

[**Scope**](../../../overview.md#scopes): **Project**, **Scene**.

# Attributes

![The On UDP Stop Node Attributes.](../../../../.gitbook/assets/onudpstopatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Configuration`|**Drop-Down**|The desired _UDP_ server, which refers back to the selections made under *UDP* in the [**Project Settings**](../../../../modules/project-settings/README.md).| 



# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**On UDP Start**](onudpstart.md)

