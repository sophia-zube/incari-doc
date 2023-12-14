# Overview

![The Set Stroke Width Node.](../../../.gitbook/assets/setstrokewidthnode2d.png)

The **Set Stroke Width Node** sets the `Stroke` width of the inputted **Object** from a **Scene2D**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Set Stroke Width Node Attributes.](../../../.gitbook/assets/setstrokewidthatts2d.png)

|Attribute|Type|Description|
|---|---|---|
|`Width`|**Float**|The width to be set for the *2D* **Object's** `Stroke`, if one is not provided in the **Input Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the *2D* **Object** that will have its `Stroke` width set.|
|`Width`|**Float**|The desired `Stroke` width of the inputted *2D* **Object**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Get Stroke Width**](getstrokewidth.md)

