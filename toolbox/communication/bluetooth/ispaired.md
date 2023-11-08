# Overview

![The Is Bluetooth Device Paired Node.](../../../.gitbook/assets/isbluetoothdevicepaired.png)

The **Is Bluetooth Device Paired Node** checks the pairing status of a *Bluetooth* device to the [**Bluetooth Plugin**](../../../modules/plugins/communication/bluetoothmanager.md).

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Bluetooth Address`|**String**|The unique *Bluetooth* identifier that is associated with a *Bluetooth* device.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Is Paired`|**Bool**|Returns *true* if the device is paired and *false* if not.|
|`On Error`(►)|**Pulse**|An **Event Pulse** that fires in the event of an error.|
|`Error Message`|**String**|The error message in the event of an error.|
|`Error Bluetooth Address`|**String**|The *Bluetooth* address associated with the error.|

