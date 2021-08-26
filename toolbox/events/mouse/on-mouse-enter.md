# On Mouse Enter

## Overview

![The On Mouse Enter Node.](../../../.gitbook/assets/node-on-mouse-enter.png)

**On Mouse Enter** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor enters an **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which entering with the cursor triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the X-Y coordinates of the point of entry with respect to the bottom left of the **Screen**. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

