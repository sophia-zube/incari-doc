# Overview

![The Get Text Node.](../../../.gitbook/assets/gettextnode.png)

The **Get Text Node** returns the text of the inputted **Object**, such as [**Text**](../../../objects-and-types/scene2d-objects/gui/text.md), [**Text Area**](../../../objects-and-types/scene2d-objects/gui/textarea.md), and [**Text Input**](../../../objects-and-types/scene2d-objects/gui/textinput.md).

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The **Object** whose text will be returned.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Text`|**String**|The text from the **Object** given as input.|



