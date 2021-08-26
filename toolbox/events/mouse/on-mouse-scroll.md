# On Mouse Scroll

## Overview

![The On Mouse Scroll Node.](../../../.gitbook/assets/node-on-mouse-scroll.png)

**On Mouse Scroll** is an **Event Listener** **Node** used for executing a **Logic Branch** when the user scrolls over an **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which scrolling over triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** whose Y coordinate indicates the direction and speed of the scrolling. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

