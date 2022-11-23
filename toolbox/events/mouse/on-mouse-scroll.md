# On Mouse Scroll

## Overview

![The On Mouse Scroll Node.](../../../.gitbook/assets/onmousescrollupdatedimage.png)

**On Mouse Scroll** is an **Event Listener** **Node** used for executing a **Logic Branch** when the user scrolls either over an **Object** or anywhere in the **Screen**.

The **Attributes** allow the user to choose whether the `Event Base` is a specific **Object** or the entire **Screen**.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On Mouse Scroll Node Attributes.](../../../.gitbook/assets/onmousescrollattributes.png)

### Event Base

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Event Base` | **Drop-down** | Whether the **Logic** will be triggered when the cursor enters a particular **Object** or the **Screen**.  |

## Inputs

Note: **Input Sockets** only available when `Event Base` is set to `Object`.

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | The **Object** in which scrolling over triggers the **Logic Branch**. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** whose Y-coordinate indicates the direction and speed of the scrolling. |
| `Object ID` | **ObjectID** |  The **Object ID** of the **Object** where the scroll occurs. If there is no **Object** on that part of the **Screen**, the output is the **Object ID** `00000000-0000-0000-0000-000000000000`. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

