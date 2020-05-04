# Overview

![](../../.gitbook/assets/node-add.png)

**Add** is a *basic arithmetic operation* **Node**, that returns the sum of all of the values provided in the `Input` **Sockets**.

This is the equivalent of the addition (`+`) operation in computer science and mathematics.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Input` **Sockets**.|
|`Default Inputs`|*Defined in the `Data Type` **Attribute***.|The amount of `Input` **Sockets** and their default values if they have no data connected to them.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input [n]`|*Defined in the `Data Type` **Attribute***.|The values to be added together.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|*Defined in the `Data Type` **Attribute***.|The sum of all of the values provided in the `Input` **Sockets**.|