# Overview

![](../../../.gitbook/assets/node-multiply.png)

**Multiply** returns the result of all **Values** provided in the **Input Sockets**, multiplied together.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of **Data** that will be plugged into the `Input` **Sockets**.|
|`Count`|**Int**|The number of **Data Input Sockets** the **Node** will have.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input [n]`|*Defined in the* `Data Type` ***Attribute***.|The **Values** to be multiplied together.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|*Defined in the* `Data Type` ***Attribute***.|The result of all of the **Input Values** multiplied together.|