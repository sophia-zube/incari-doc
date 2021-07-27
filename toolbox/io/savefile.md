# Overview

![The Savefile Node.](../../.gitbook/assets/Savefile.jpg)

**Save File** is an _io_, or '_input/output_'  **Node** which allows one to store a specified file.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`File's Local Path`|**User Input**|The `file path` local to the user's device|
|`Overwrite File if Exists`|**Bool**|If the `file path` already exists, the current data will replace any existing data in the existing file

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**|
|`Content`|Defined in the **Logic Editor**|The project content that needs to be saved

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
