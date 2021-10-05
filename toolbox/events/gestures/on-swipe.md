# On Swipe

## Overview

![The On Swipe Node.](../../../.gitbook/assets/node-on-swipe.png)

**On Swipe** is an **Event Listener** **Node** used for executing a **Logic Branch** after a swipe on an **Object**.

## Attributes

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** in which a swipe triggers the **Logic Branch**. |

### Button

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Mouse Button` | **Drop-down** | Whether a swipe with the left, middle, or right button of the mouse will trigger the **Logic**. |

### Swipe

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Swipe Direction` | **Drop-down** | The direction in which a swipe will trigger the **Logic**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Distance` | **Vector2** | Length of the swipe in the X and Y directions. |

## See Also

* [**Gestures**](./)

