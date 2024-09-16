# Overview

![The Unpair Bluetooth Device Node.](../../../.gitbook/assets/unpairbluetoothdevicenode20241.png)

**Unpair Bluetooth Device** attempts to unpair a given *Bluetooth* device that may have been previously discovered by the [**Scan For Bluetooth Devices Node**](scanforbluetoothdevices.md). A more detailed explanation of this process can be found [here](README.md#bluetooth-guideline).

The **Node** only schedules the unpairing process and then returns immediately. This means that it is possible to trigger the **Node** multiple times with different inputs, resulting in consecutive unpairing attempts. This is the reason for returning the error *Bluetooth* address, as it properly attributes the error to the relevant device. 

**Bluetooth Communication** in **Incari** is available as a plugin and is enabled as default. However, in the case that it is disabled in the **Plugins Editor**, **Unpair Bluetooth Device** will not show up in the [**Toolbox**](../../overview.md). Please refer to the [**Plugins Editor**](../../../modules/plugins/README.md) to find out more information.

It is important to note that while the **Unpair Bluetooth Device** disconnects from a **Bluetooth** device (like a phone), it will not finish unpairing when the **Node** is executed. This will lead to the **Logic** attached to its **Output Pulse** not to work even though there is technically nothing wrong. In order to avoid this, it is necessary to use the [**On Bluetooth Device Unpaired Node**](events/onbluetoothdevicepaired.md) instead. This way, the **Logic** will only execute once the **Bluetooth** device has definitely been unpaired from.

Again, the user must first use the **Unpair Bluetooth Device Node** to unpair from a device. Separately, the **On Bluetooth Device Unpaired Node** can be used to execute the desired **Communication Logic**.

![Pair Bluetooth Device Node and On Bluetooth Device Paired Configuration.](../../../.gitbook/assets/unpairbluetoothonbluetoothdeviceunpairedexample2.png)

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Bluetooth Address`|**String**|The unique *Bluetooth* identifier that is associated with a *Bluetooth* device. This can be discovered by the [**Scan For Bluetooth Devices Node**](scanforbluetoothdevices.md).|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`On Error`(►)|**Pulse**|An **Event Pulse** that fires in the event of an error, namely that unpairing failed.|
|`Error Message`|**String**|The error message in the event of an error.|
|`Bluetooth Address`|**String**|The *Bluetooth* address of the device for which the pairing failed, in the event of an error|

# See Also

* [**Pair Bluetooth Device**](pairbluetoothdevices.md)

