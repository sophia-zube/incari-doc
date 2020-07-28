# Overview

![The Set Active Node.](../../../.gitbook/assets/toolbox/incari/list/set-active.PNG)

**Set Active** activates or deactivates a **List** **Object** in a **Scene**. It accepts a **List** **Object** and boolean value `Is Active`. If `Is Active` is positive, then the **List** **Object** is activated otherwise it is deactivated.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Object`|**ObjectID**|The target **List** **Object** you wish to activate or deactivate, if one is not provided in the `object ID` **Socket**.|
|`Default Value Is Active`|**Bool**|A default boolean switch which activates and deactivates the **List** **Object**, if no value is provided to the `Is Active` input **Socket**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The target **List** **Object** you wish to activate or deactivate.|
|`Is Active`|**Bool**|If `Is Active` is *true*, the **List** **Object** is activated, otherwise is deactivated.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also
- [**List**](objects/scene-objects/list.md)
- [**Generate List**](generate-list.md)
- [**Previous List Entry**](previous-list-entry.md)

