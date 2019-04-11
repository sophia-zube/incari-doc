# Overview

**SystemTime** is used for returning different individual parts of the current system time at the moment that the **Node** is evaluated. Values are returned as **Integers**, and therefore, have no inherent zero-padding, textual notation or suffixes.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`24h Mode`|**Bool**|Changes whether the `Hour` **Output** is given in 12 or 24 hour format.|


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs
|Output | Type   | Description   |
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Hour`|**Int**|The system's current hour, in 12 or 24 hour format (based on `24h Mode` **Attribute**).|
|`Minute`|**Int**|The system's current minute.|
|`Second`|**Int**|The system's current seconds.|
|`Millisecond`|**Int**|The system's current milliseconds.|