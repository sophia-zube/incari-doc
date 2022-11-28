# Overview

![The Set Current Directory Node.](../../.gitbook/assets/setcurrentdirectoryupdatedimage.png)

The **Set Current Directory Node** allows the user to change the current *directory*. It returns a **Boolean** of *true* or *false*, indicating whether setting it was successful or not. 

[**Scope**](../overview.md#scopes): **Project**, **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Directory`|**String**|The path name of the desired working *directory*.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Success`|**Boolean**|Returns *true* or *false*, depending on whether the given working *directory* was successfully set or not.|

# See Also

* [**Get Current Directory**](getcurrentdirectory.md)

