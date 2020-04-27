# Overview

![](../../.gitbook/assets/node-ceil.png)

**Floor** takes a numerical **Value** and returns the highest whole number, which is greater than, or equal to, the `Input` **Value**. This basically means that the **Value** is rounded up, and any non-whole number will ouput the next highest whole number.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The **Data Type** of the `Input` and `Output` **Sockets**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|*Defined in the* `Data Type` ***Attribute**.* |The **Value** to be *rounded up* to 0 decimal places.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|*Defined in the* `Data Type` ***Attribute**.* |The **Value** of `Input` after being *rounded up* to 0 decimal places.|

# External Links

- [*Floor and Ceiling Functions*](https://www.mathsisfun.com/sets/function-floor-ceiling.html) on Maths is Fun.