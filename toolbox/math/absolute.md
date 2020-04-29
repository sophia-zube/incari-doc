# Overview

![The Absolute Node.](../../.gitbook/assets/node-absolute.png)

**Absolute** takes a single numerical value and converts any negative value (per component) to its absolute/non-negative equivalent.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Input` **Socket** and will return via its `Output` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input`|*Defined in the `Data Type` **Attribute***.|The value to be converted to its non-negative equivalent.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|*Defined in the `Data Type` **Attribute***.|The non-negative equivalent of `Input`.|

# External Links

- [*Absolute value*](https://en.wikipedia.org/wiki/Absolute_value) on Wikipedia.