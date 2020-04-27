# Overview

![](../../.gitbook/assets/node-floor.png)

**Floor** takes a numerical value and rounds it *down* to the nearest whole number. This will affect each *component* separately with *data types* that are comprised of multiple components (*vectors* and *matrices*).

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Input` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input`|*Defined in the `Data Type` **Attribute***.|The value (per *component*) to be rounded *down* to 0 decimal places.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|*Defined in the `Data Type` **Attribute***.|The value of `Input` (per *component*) after being *rounded down* to 0 decimal places.|

# External Links

- [*Floor and Ceiling Functions*](https://www.mathsisfun.com/sets/function-floor-ceiling.html) on Maths is Fun.