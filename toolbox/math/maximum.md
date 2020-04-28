# Overview

![](../../.gitbook/assets/node-maximum.png)

**Maximum** compares a set of numerical inputs and returns the upper bound (maximum value) in the set.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The data type of all `Input` and `Output` **Sockets**.|
|`Inputs`|*Defined in the `Data Type` **Attribute***.|The amount of `Input` **Sockets** and their default values if they have no data connected to them.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input [n]`|*Defined in the `Data Type` **Attribute**.*|The set of values to get the upper bound from.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Maximum`|*Defined in the `Data Type` **Attribute**.*|The maximum value in the set of inputs.|

# External Links

- [*Upper and lower bounds*](https://en.wikipedia.org/wiki/Upper_and_lower_bounds) on Wikipedia.