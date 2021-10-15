# On Mouse Move

## Overview

![The On Mouse Move Node.](../../../.gitbook/assets/node-on-mouse-move.png)

**On Mouse Move** is an **Event Listener** **Node** used for executing a **Logic Branch** when the cursor moves within an **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which moving with the cursor triggers the **Logic Branch**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Position` | **Vector2** | **Vector** containing the XY-coordinates of the points through which the cursor passes with respect to the bottom left of the **Screen**. |

## See Also

* [**Events**](../)
* [**Mouse**](./)

