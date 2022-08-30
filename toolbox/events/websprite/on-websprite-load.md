# On WebSprite Load

## Overview

![The On WebSprite Load Node.](<../../../.gitbook/assets/onwebspriteloadnode - Copy.png>)

**On WebSprite Load** is an **Event Listener** **Node** used for executing a **Logic Branch** when a **Web Sprite** **Object** is loaded.

[**Scope**](../../overview.md#scopes): **Scene**, **Prefab**.

## Attributes

![The On WebSprite Load Node Attributes.](../../../.gitbook/assets/onwebspriteloadattributes.png)

### Object

| Attribute | Type         | Description                                                                                                                        |
| --------- | ------------ | ---------------------------------------------------------------------------------------------------------------------------------- |
| `Object`  | **ObjectID** | The **Web Sprite** **Object** that triggers the **Logic Branch** on loading, if none is given in the `Object ID` **Input Socket**. |

## Inputs

| Input           | Type         | Description                                                                        |
| --------------- | ------------ | ---------------------------------------------------------------------------------- |
| `Object ID`     | **ObjectID** | The **Web Sprite** **Object** that triggers the **Logic Branch** on loading.       |
| `Subscribe` (►) | **Pulse**    | An **Input Pulse** that needs to be triggered to start listening to the **Event**. |

## Outputs

| Output             | Type         | Description                                                                                                                            |
| ------------------ | ------------ | -------------------------------------------------------------------------------------------------------------------------------------- |
| _Pulse Output_ (►) | **Pulse**    | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Object ID`        | **ObjectID** | The **Web Sprite** **Object** received as **Input**.                                                                                   |

## See Also

* [**Web Sprite Objects**](../../../objects-and-types/scene-objects/web-sprite.md)
* [**WebSprite Nodes**](../../incari/websprite/)
