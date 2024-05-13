# CANopen

## Introduction

The **CANopen Nodes** provide a means for the user to perform several actions within the _CANopen_ protocol. *CANopen* is a form of communication that extends the functionality of the [*CAN*](../can/README.md) (Controller Area Network) protocol. It provides a standardized framework for defining communication and application layer protocols for devices and systems employing *CAN* as their underlying physical layer. This standardization facilitates seamless interconnection and interoperability among a diverse range of devices, including but not limited to sensors and motor controllers.

To use the **CANopen Nodes** in **Incari**, the user needs to locate the [**CANopen Attributes**](../../../modules/project-settings/CANopen.md) in **Project Settings** and upload a _DFC_ file.

## CANopen Guideline

These are the guidelines for incorporating **CANopen Communication** into a **Project**.

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communication Introduction page.
* Once the connection has been established, there are several **Nodes** that cover important functions of **CAN Communication**.
  * [**CANopen Send**](canopensend.md) sends a **CANopen** message when a signal is received. 
  * [**On CANopen Receive**](events/oncanopenreceive.md) executes once a message is received.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

## Contents

* [**CANopen Send**](canopensend.md)
* [**CANopen Start**](canopenstart.md)
* [**CANopen Stop**](canopenstop.md)
* [**Events**](events/)
  * [**On CANopen Receive**](events/oncanopenreceive.md)
  * [**On CANopen Start**](events/oncanopenstart.md)
  * [**On CANopen Stop**](events/oncanopenstop.md)

## External Links

* Introduction to [*CANopen*](https://www.csselectronics.com/pages/canopen-tutorial-simple-intro).
* Differences between [*CAN and CANopen*](https://www.rfwireless-world.com/Terminology/Difference-between-CAN-and-CANopen.html).