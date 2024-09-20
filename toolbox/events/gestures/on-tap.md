# On Tap

## Overview

![The On Tap Node.](../../../.gitbook/assets/ontapnode20241.png)

**On Tap** is an **Event Listener** **Node** used for executing a **Logic Branch** after a tap on an **Object**.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes


![The On Tap Node Attributes.](../../../.gitbook/assets/ontapattributesupdate.png)

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a tap triggers the **Logic Branch**, if none is given in the `Object ID` **Input Socket**. |

### Button

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mouse Button` | **Drop-down** | Whether the left, middle, or right button of the mouse will trigger the **Logic**. |

### Event base

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Event Base` | **Drop-down** | Whether the base of the **Event** is a particular **Object** or the entire **Screen**.|

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which a tap triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `IsLongClick` | **Bool** | _True_ when the button is pressed longer than usual. |
| `Object ID` | **ObjectID** | The **Object** received as **Input**. | 
|`Event ID`| **ObjectID**| The ID of the current **Event**. This can be connected to the [**Unsubscribe Node**](../unsubscribe.md) to unsubscribe from the **Event**.|

## See Also

* [**Gestures**](./)

