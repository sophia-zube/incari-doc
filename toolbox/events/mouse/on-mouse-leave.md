# On Mouse Leave

## Overview

![The On Mouse Leave Node.](../../../.gitbook/assets/node-on-mouse-leave.png)

**On Mouse Leave** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor leaves an **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which leaving with the cursor triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the XY-coordinates of the point of exit with respect to the bottom left of the **Screen**. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

