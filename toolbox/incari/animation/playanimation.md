# Overview

![The Playanimation Node.]() !!!!Need Image!!!! 

**Play Animation** is an *animation* **Node** that can be found under **Incari** in the node library and a **CustomID** type variable is required as input. It is used to play an **Animation** when the project is run and can be used in conjunction with **Pause Animation** and **Stop Animation**

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`File`|**User Input**| The animation file the user wishes to manipulate. The user can drag a file from their library or select a file from a file tree. The icons to the right allow for the user to confirm selection, highlight the **Asset** in the **Asset Manager**, and remove the selection.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|*InstanceID*|**CustomID**|The assigned **Instance** of the **Animation**|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|*InstanceID*|**CustomID**|The previously assigned **Instance** of the **Animation**|
|*OnPlay*|**Pulse**|Flows to additional actions following **Play Animation**|
|*OnPause*|**Pulse**|Flows to additional actions following **Play Animation** (most likely **Pause Animation**|
|*OnStop*|**Pulse**|Flows to additional actions following **Play Animation** (most likely **Stop Animation**)


