# On Mouse Enter

## Overview

![The On Mouse Enter Node.](../../../.gitbook/assets/onmouseenterupdatedimage.png)

**On Mouse Enter** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor enters an **Object**.

The **Attribute** `Event Base` allows the user to choose whether the **Node** is triggered only for a specific **Object** or for any **Object** in the **Screen**.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On Mouse Enter Node Attributes.](../../../.gitbook/assets/onmouseenterattributes.png)

### Event Base

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Event Base` | **Drop-down** | Whether the **Logic** will be triggered when the cursor enters a particular **Object** or the **Screen**.  |

## Inputs

Note: **Input Sockets** only available when `Event Base` is set to `Object`.

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which entering with the cursor triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the XY-coordinates of the point of entry with respect to the bottom left of the **Screen**. |
| `Object ID` | **ObjectID** | The **Object ID** of the **Object** entered. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

