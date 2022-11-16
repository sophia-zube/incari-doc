# On ImageSequence Play

## Overview

![The On ImageSequence Play Node.](../../../.gitbook/assets/onimagesequenceplayupdatedimage.png)

**On ImageSequence Play** is an **Event Listener** **Node** used for executing a **Logic Branch** when an **Image Sequence** starts playing.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On ImageSequence Play Node Attributes.](../../../.gitbook/assets/onimagesequenceplayattributes.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | **Image Sequence** that triggers the **Logic Branch** when played, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| `Object ID` | **ObjectID** | **Image Sequence** that triggers the **Logic Branch** when played. |
| `Subscribe` (►)|**Pulse** | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Object ID` | **ObjectID** | The **Image Sequence** received as **Input**. | 

## See Also

* [**Image Sequence**](./)

