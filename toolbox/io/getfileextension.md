# Overview

![The Get File Extension Node.](../../.gitbook/assets/getfileextensionupdatedimage.png)

The **Get File Extension** **Node** outputs the file _extension_ of a file whose _path_ has to be given as input.

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Path` | **String** | The _path_ of the file whose _extension_ is to be obtained. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Extension` | **String** | The file _extension_ of the file whose _path_ was given as input. |


# External Links

* [_Filename extension_](https://en.wikipedia.org/wiki/Filename_extension) on Wikipedia.

