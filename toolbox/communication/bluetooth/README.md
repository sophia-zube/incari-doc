## Introduction

The **Bluetooth Nodes** provide a means for the user to perform several actions within the *Bluetooth* standard. *Bluetooth* allows for communication between wireless and fixed devices in the short range, like when a car connects to a mobile phone. 

## Bluetooth Guideline

These are the guidelines for incorporating **Bluetooth Communication** into a **Project**.

* To properly start a connection with a device, or devices, the user must start with the [**Scan For Bluetooth Devices Node**](scanforbluetoothdevices.md).  
* Once a connection with a **Bluetooth** device is made, it is possible to pair. Use [**Pair Bluetooth Device**](pairbluetoothdevices.md) to initiate the pairing. Separately, use [**On Bluetooth Device Paired**] to execute any following **Logic**. This is to make sure the connection is successfully finished being established before doing anything.  Only then is it possible to use the several **Nodes** that cover important functions of **Bluetooth Communication**.
  * [**Is Bluetooth Device Paired**](ispaired.md) returns *true* or *false* when a connection has successfully been made with the given *Bluetooth* address, or an error message if there is an error.
  * [**Retrieve Call History**](retrievecalhistory.md) returns the call history of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Retrieve Phonebook**](retrievephonebook.md.md) returns the call history of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Scan For Bluetooth Devices**](websocketsend.md) searches for **Bluetooth** devices in the general vicinity and returns **Dictionary** of them on success, or an error message if there is an error. 
* To terminate the connection, use the [**Unpair Bluetooth Device Node**](unpairbluetoothdevices.md) to start disconnecting. Separately, use the **On Bluetooth Device Unpaired Node** to execute any following **Logic**. This is to make sure the connection is stopped completely before doing anything.

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
