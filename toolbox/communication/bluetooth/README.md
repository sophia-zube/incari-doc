## Introduction

The **Bluetooth Nodes** provide a means for the user to perform several actions within the *Bluetooth* standard. *Bluetooth* allows for communication between wireless and fixed devices in the short range, like when a car connects to a mobile phone. 

## Bluetooth Guideline

These are the guidelines for incorporating **Bluetooth Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **Bluetooth Communication**.
  * [**Is Bluetooth Device Paired**](ispaired.md) returns *true* or *false* when a connection has successfully been made with the given *Bluetooth* address, or an error message if there is an error.
  * [**Retrieve Call History**](retrievecalhistory.md) returns the call history of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Retrieve Phonebook**](retrievephonebook.md.md) returns the call history of a **Bluetooth** device (or devices), or an error message if there is an error. 
  * [**Scan For Bluetooth Devices**](websocketsend.md) searches for **Bluetooth** devices in the general vicinity and returns **Dictionary** of them on success, or an error message if there is an error. 
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

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
