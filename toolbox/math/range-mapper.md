# Overview

![The Range Mapper Node.](../../.gitbook/assets/node-range-mapper.png)

**Range Mapper** transforms a single numerical value, from its relative position in a given reference range, to a new value within a second target range.

In the event that `Input` is outside of the reference (input) range, `Clamp` determines whether or not the `Output` should be clamped within the target range, or if it should be transformed to its relative value outside of the range.

|`Input`|Input Range|Output Range|`Clamp`|`Output`|
|---|---|---|---|---|
|0.5|0-1|0-100|✔ or ✖|50|
|20|0-100|100-0|✔ or ✖|80|
|1.5|0-1|0-360|✔|360|
|1.5|0-1|0-360|✖|540|

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Input`, `Input From`, and `Input To` **Sockets**.|
|`From`|*Defined in the `Data Type` **Attribute***.|The default lower boundary of the reference range, if there is nothing attached to the `Input From` **Socket**.|
|`To`|*Defined in the `Data Type` **Attribute***.|The default upper boundary of the reference range, if there is nothing attached to the `Input To` **Socket**.|

## Outputs

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Output From` and `Output To` **Sockets** and will return via its `Output` **Socket**.|
|`From`|*Defined in the `Data Type` **Attribute***.|The default lower boundary of the target range, if there is nothing attached to the `Output From` **Socket**.|
|`To`|*Defined in the `Data Type` **Attribute***.|The default upper boundary of the target range, if there is nothing attached to the `Output To` **Socket**.|
|`Clamp`|**Bool**|Whether or not the `Output` should be clamped within the target range, or if it should be transformed to its relative value outside of the range.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input`|*Defined in the `Data Type` **Attribute***.|The value to be transformed/mapped.|
|`Input From`|*Defined in the `Data Type` **Attribute***.|The lower boundary of the reference range.|
|`Input To`|*Defined in the `Data Type` **Attribute***.|The upper boundary of the reference range.|
|`Output From`|*Defined in the `Data Type` **Attribute***.|The lower boundary of the target range.|
|`Output To`|*Defined in the `Data Type` **Attribute***.|The upper boundary of the target range.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|*Defined in the `Data Type` **Attribute***.|The transformed value.|

# See Also

- [**Clamp**](clamp.md)