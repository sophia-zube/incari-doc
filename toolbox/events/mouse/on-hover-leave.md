# On Hover Leave

## Overview

![The On Hover Leave Node.](../../../.gitbook/assets/node-on-hover-leave.png)

**On Hover Leave** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor stops hovering over an **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which stop hovering triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the XY-coordinates of the point of exit with respect to the bottom left of the **Screen**. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

## External Links

* [_Mouseover_](https://en.wikipedia.org/wiki/Mouseover) on Wikipedia.

