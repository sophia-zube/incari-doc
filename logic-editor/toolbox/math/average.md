# Overview

![](../../../.gitbook/assets/node-average.png)

**Average** takes two or more **Float Values** and calculates the *arithmetic mean*, which is the total *sum* of the **Inputs** divided by the total *number* of **Inputs**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Count`|**Int**|The number of **Data Input Sockets** the **Node** will have.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input [n]`|**Float**|The **Values** that will be added together, and divided by `Count`.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Float**|The *arithmetic mean* of all of the **Input Values**.|

# External Links

- [*Arithmetic Mean: What it is and How to Find it*](https://www.statisticshowto.datasciencecentral.com/arithmetic-mean/) on Statistics How To.