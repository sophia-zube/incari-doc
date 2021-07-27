# Overview

![The Loadfile Node.](../../.gitbook/assets/Loadfile.jpg)

**Load File** is an _io_, or '_input/output_',  **Node** which allows one to load a specified file, such as a previously saved variable or **Dictionary**. In the latter case, the **JSON Pass** **Node** must be used first. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`File`|**User Input**| The user can drag a file from their library or select a file from a file tree. The icons to the right allow for the user to confirm selection, highlight the **Asset** in the **Asset Manager**, and remove the selection.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|*Content*| Defined in the the **Logic Editor**| The project content that is to be loaded.

