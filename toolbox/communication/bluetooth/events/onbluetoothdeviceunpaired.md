
# Overview

![The On Bluetooth Device Unpaired Node.](../../../../.gitbook/assets/onbluetoothdeviceunpaired.png)

The **On Bluetooth Device Unpaired Node** signals that a *Bluetooth* device was unpaired successfully.

**Bluetooth Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, it will not appear in the **Project Settings** and **On Bluetooth Device Unpaired** will not show up in the [**Toolbox**](../../../overview.md). Please refer to the [**Plugins Editor**](../../../../modules/plugins/README.md) to find out more information.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.



# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Bluetooth Address`|**String**|The *Bluetooth* address of the unpaired device.|

# See Also

* [**On Bluetooth Device Paired**](onbluetoothdevicepaired.md)



