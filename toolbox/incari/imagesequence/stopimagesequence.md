# Overview

![The Stop ImageSequence Node.](../../../.gitbook/assets/stopimagesequence.png)

The **Stop ImageSequence Node** ends an **ImageSequence** already playing during a session.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **Object**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the target **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Play ImageSequence**](playimagesequence.md)
* [**Pause ImageSequence**](pauseimagesequence.md)
* [**Resume ImageSequence**](resumeimagesequence.md)