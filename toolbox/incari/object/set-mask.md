# Overview

![The Set Mask Node.](../../../.gitbook/assets/setmasknode.png)

The **Set Mask Node** sets, or reassigns, the current **Mask** of an **Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the desired **Object**, whose **Mask** will be set.|
|`Mask Object ID`|**ObjectID**|The ID of the **Mask** to set for the desired **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|



