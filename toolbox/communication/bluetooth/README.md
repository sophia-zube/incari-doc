## Introduction

The **Bluetooth Nodes** provide a means for the user to perform several actions within the *Bluetooth* standard. *Bluetooth* allows for communication between wireless and fixed devices in the short range, like when a car connects to a mobile phone. More information can be found [*here*](https://en.wikipedia.org/wiki/Bluetooth).

## Bluetooth Guideline

These are the guidelines for incorporating **Bluetooth Communication** into a **Project**.

* Unless a device's *Bluetooth* address is already known or has been previously retrieved through other means, one should use the [**Scan For Bluetooth Devices Node**](scanforbluetoothdevices.md) to discover any devices in the nearby vicinity. This will return all pairable devices in range as well as their Bluetooth addresses.  
* Once a **Bluetooth** device has been discovered, it is possible to attempt pairing. Use [**Pair Bluetooth Device**](pairbluetoothdevices.md) to initiate the pairing. Separately, use [**On Bluetooth Device Paired**](events/onbluetoothdevicepaired.md) to execute any following **Logic** after pairing. This is to make sure pairing is successfully finished being established before doing anything.  Only then is it possible to use the several **Nodes** that cover important functions of **Bluetooth Communication**.
  * [**Is Bluetooth Device Paired**](ispaired.md) returns *true* or *false* if a device has been paired with (even if it is out of range), or an error message if there is an error.
  * [**Retrieve Call History**](retrievecalhistory.md) returns the call history of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Retrieve Phonebook**](retrievephonebook.md) returns the phonebook of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Scan For Bluetooth Devices**](scanforbluetoothdevices.md) searches for **Bluetooth** devices in the general vicinity and returns **Dictionary** of them on success, or an error message if there is an error. 
* To revoke access rights to a device (essentially removing it as a possibility for interacting with), use the [**Unpair Bluetooth Device Node**](unpairbluetoothdevices.md) to start unpairing. Separately, use the **On Bluetooth Device Unpaired Node** to execute any following **Logic**. This is to make sure the device is removed properly before doing anything.

## Contents

* [**Events**](events/README.md)
  * [**On Bluetooth Device Paired**](events/onbluetoothdevicepaired.md)
  * [**On Bluetooth Device Unpaired**](events/onbluetoothdeviceunpaired.md)
* [**Is Bluetooth Device Paired**](ispaired.md)
* [**Pair Bluetooth Device**](pairbluetoothdevices.md)
* [**Retrieve Call History**](retrievecallhistory.md)
* [**Retrieve Phonebook**](retrievephonebook.md)
* [**Scan For Bluetooth Devices**](scanforbluetoothdevices.md)
* [**Unpair Bluetooth Device**](unpairbluetoothdevices.md)


# External Links

* More about *Bluetooth* on [*Wikipedia*](https://en.wikipedia.org/wiki/Bluetooth).