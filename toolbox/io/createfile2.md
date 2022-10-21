# Overview

![The Create File Node.](../../.gitbook/assets/createfile_2.png)

The **Create File Node** creates a file in a location given by the user. The file _path_, including the name of the file to be created and its extension, has to be given as input and the output is a **Boolean** indicating whether the operation was successful. Thus, a valid *path* to be given as input is of the form `C:\Users\User\MyIncariProjects\MyProject\Assets\MyFiles\file.txt`.

Note that files can only be created within the **Project Asset** folder.

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Path` | **String** | The *path* of the file to be created. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Success` | **Bool** | Returns _true_ or _false_, depending on whether the file creation was successful.  |

# See Also

* [**Remove**](remove.md)
* [**Load File**](loadfile.md)
* [**Save File**](savefile.md)