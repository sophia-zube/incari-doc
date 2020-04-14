# Overview

![](../../../.gitbook/assets/node-clamp.png)

**Clamp** limits a **Numerical Value** to a given range, so that it isn't lower than the lower boundary, or higher than the upper boundary.

It is often used as a way of ens

|`Value`|`From`|`To`|`Result`|
|---|---|---|---|
|50|0|100|50|
|120|0|100|100|
|-20|0|100|0|
|-270|-180|180|-180|
|-20, 1100|0, 0|1920, 1080|0, 1080|

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of **Data** that will be plugged into the `Input` **Sockets**.|
|`From`|*Defined in the* `Data Type` ***Attribute**.*|The default **Value** of the lower boundary of the range, if there is nothing attached to the `From` **Input Socket**.|
|`To`|*Defined in the* `Data Type` ***Attribute**.*|The default **Value** of the upper boundary of the range, if there is nothing attached to the `To` **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Value`|*Defined in the* `Data Type` ***Attribute**.*|The **Value** to be clamped within the range defined in `From` and `To`.|
|`From`|*Defined in the* `Data Type` ***Attribute**.*|The **Value** of the lower boundary of the range.|
|`To `|*Defined in the* `Data Type` ***Attribute**.*|The **Value** of the upper boundary of the range.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Result`|*Defined in the* `Data Type` ***Attribute**.*|The clamped **Value**, based on the three **Inputs**.|