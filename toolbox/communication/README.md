# Communication

## Introduction

The **Communication Nodes** \(**CAN**, **HTTP**, **MQTT**, and **Serial**\) represent the different messaging protocols and ways of communicating between devices that each one employs.

## General Guideline

* Locate the desired communications protocol in [**Project Settings**](../../modules/project-settings.md). Attach all necessary files and data. 
* In the **Logic Editor**, use the protocol's **Start Node** to initiate the connection. Separately, use the protocol's **On Start Node** to execute any following **Logic**. This is to make sure the connection is finished being established before doing anything.
* Use any combination of the protocol's **Nodes** to provide **Communication** capabilities to the **Project**. The protocols provided by **Incari** are [**CAN**](can/README.md), [**HTTP**](http/README.md), [**MQTT**](mqtt/events/README.md), [**Serial**](serial/README.md) communication.
* To end the connection, use the protocol's **Stop Node** to start disconnecting. Separately, use the protocol's **On Stop Node** to execute any following **Logic**. This is to make sure the connection is stopped completely before doing anything. 

## Content

* [**CAN**](can/)
* [**HTTP**](http/)
* [**MQTT**](mqtt/)
* [**Serial**](serial/) 

