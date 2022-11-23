# On Mouse Leave

## Overview

![The On Mouse Leave Node.](../../../.gitbook/assets/onmouseleaveupdatedimage.png)

**On Mouse Leave** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor leaves an **Object**.

The **Attribute** `Event Base` allows the user to choose whether the **Node** is triggered only for a specific **Object** or for any **Object** in the **Screen**.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On Mouse Leave Node Attributes.](../../../.gitbook/assets/onmouseleaveattributes%20-%20Copy.png)

### Event Base

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Event Base` | **Drop-down** | Whether the **Logic** will be triggered when the cursor enters a particular **Object** or the **Screen**.  |

## Inputs

Note: **Input Sockets** only available when `Event Base` is set to `Object`.

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which leaving with the cursor triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the XY-coordinates of the point of exit with respect to the bottom left of the **Screen**. |
| `Object ID` | **ObjectID** | The **Object ID** of the **Object** left.|

## See Also

* [**Events**](../)
* [**Mouse**](./)

