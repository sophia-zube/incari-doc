# Get Paint Opacity

This **Node** has different versions based on whether `Fill` or `Stroke` is set in the **Attributes**. 


{% tabs %}
{% tab title="Fill" %}

## Overview

![The Get Fill Paint Opacity Node.](../../../.gitbook/assets/getfillpaintopacitynode.png)

The **Get Fill Paint Opacity Node** returns the fill's `Opacity` -- meaning how opaque or transparent it appears -- of the selected **Object** at the specified layer indicated by the `Index`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get Fill Paint Opacity Node Attributes.](../../../.gitbook/assets/getfillpaintopacityatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|Can be either `Fill` or `Stroke`. In this case, `Fill` has been chosen.|
|`Index`|**Int**|Determines the layer of the fill content, if one is not provided in the **Input Socket**. It works in a top to bottom way, where 0 is the top layer and increasing layers are below it.|


## Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its fill's `Opacity` returned.|
|`Index`|**Int**|The index of the fill’s layer.| 

## Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Opacity`|**Float**|The fill's opacity of the selected **Object** at the specified layer.|

{% endtab %}

{% tab title="Stroke" %}


## Overview

![The Get Stroke Paint Opacity Node.](../../../.gitbook/assets/getstrokepaintopacitynode.png)

The **Get Stroke Paint Opacity Node** returns the stroke's `Opacity` -- meaning how opaque or transparent it appears -- of the selected **Object** at the specified layer indicated by the `Index`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Set Stroke Paint Opacity Node Attributes.](../../../.gitbook/assets/getstrokepaintopacityatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|Can be either `Fill` or `Stroke`. In this case, `Stroke` has been chosen.|
|`Index`|**Int**|Determines the layer of the fill content, if one is not provided in the **Input Socket**. It works in a top to bottom way, where 0 is the top layer and increasing layers are below it.|

## Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its stroke's `Opacity` returned.|
|`Index`|**Int**|The index of the stroke's layer.| 

## Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Opacity`|**Float**|The stroke's opacity of the selected **Object** at the specified layer.|


{% endtab %}
{% endtabs %}

# See Also

* [**Set Paint Opacity**](setpaintopacity.md)



