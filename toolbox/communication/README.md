# Communication

## Introduction

The **Communication Nodes** \(**Bluetooth**, **CAN**, **HTTP**, **MAVLink**, **MQTT**, **Serial**, **Socket.IO**, **TCP**, **UDP**, and **WebSocket**\) represent the different messaging protocols and ways of communicating between devices that each one employs. 

**Bluetooth**, **MAVLink**, **Serial**, **Socket.IO**, **TCP**, **UDP**, and **WebSocket are available as plugins. For more information, check out the [**Plugins Module**](../../modules/plugins/README.md)

The following guideline explains the specific set-up required to implement **Communication** in **Incari**.

## General Guideline

These are the general guidelines for incorporating all **Communication** protocols into a **Project**, except for **Bluetooth**. This includes how to start a connection, the **Nodes** that can be used and how to use them, as well as how to stop a connection. For **Bluetooth**, please refer to its specific guide [here](bluetooth/README.md).

* Locate the desired communications protocol in [**Project Settings**](../../modules/project-settings/README.md). Attach all necessary files and data.
* In the **Logic Editor**, use the protocol's **Start Node** to initiate the connection. Separately, use the protocol's **On Start Node** to execute any following **Logic**. This is to make sure the connection is successfully finished being established before doing anything.
* Use any combination of the protocol's **Nodes** to provide **Communication** capabilities to the **Project**. The protocols supported by **Incari** which use this guideline are [**CAN**](can/README.md), [**HTTP**](http/README.md), [**MAVLink**](mavlink/README.md), [**MQTT**](mqtt/README.md), [**Serial**](serial/README.md), [**Socket.IO**](socketio/README.md), [**TCP**](tcp/README.md), [**UDP**](udp/README.md), and [**WebSocket**](websocket/README.md) communication. For more information on each protocol, visit their respective page.
* To terminate the connection, use the protocol's **Stop Node** to start disconnecting. Separately, use the protocol's **On Stop Node** to execute any following **Logic**. This is to make sure the connection is stopped completely before doing anything. 

## Content

* [**Bluetooth**](bluetooth/)
* [**CAN**](can/)
* [**HTTP**](http/)
* [**MAVLink**](mavlink/)
* [**MQTT**](mqtt/)
* [**Serial**](serial/) 
* [**Socket.IO**](socketio/)
* [**TCP**](tcp/)
* [**UDP**](udp/)
* [**WebSocket**](websocket/)

