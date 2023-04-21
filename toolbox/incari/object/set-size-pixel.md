# Set Size


This **Node** has different versions for [**Scenes**](../../../objects-and-types/project-objects/scene.md) and [**Scene2Ds**](../../../objects-and-types/project-objects/scene2d.md). Find in the tabs below the documentation for both versions.

{% tabs %}

{% tab title="Scene" %}

## Overview

![The Set Size Node.](../../../.gitbook/assets/setsize3dnode.png)

The **Set Size Node** sets the $$X$$, $$Y$$, and $$Z$$ values of a **3D Object's** `Size`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Set Size Node Attributes.](../../../.gitbook/assets/setsize3datts.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Size` | **Vector2** | The desired `Size` values of the **Object**, if one is not provided in the `Size` **Socket**. |
## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Scene Object** whose `Size` you wish to return. |
| `Size` | **Vector3** | A 3-dimensional **Vector** that contains the $$X$$, $$Y$$, and $$Z$$ `Size` values of the target **Scene Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |


{% endtab %}

{% tab title="Scene2D" %}

## Overview

![The Set Size Node.](../../../.gitbook/assets/setsizenode.png)

The **Set Size Node** sets the $$X$$ and $$Y$$ values of a **2D Object's** `Size`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Set Size Node Attributes.](../../../.gitbook/assets/setsizeatts.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Size` | **Vector2** | The desired `Size` values of the **Object**, if one is not provided in the `Size` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object** whose `Size` you wish to set. |
| `Size` | **Vector2** | A 2-dimensional **Vector** that contains $$X$$ and $$Y$$ `Size` values of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

{% endtab %}

{% endtabs %}



## See Also

* [**Set Position**](set-position-pixel.md)
* [**Set Rotation**](set-rotation-pixel.md)

