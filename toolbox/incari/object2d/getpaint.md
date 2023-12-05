# Get Paint

This **Node** has different versions based on whether `Fill` or `Stroke` is chosen in the **Attributes**. 


{% tabs %}
{% tab title="Fill" %}

## Overview

![The Get Fill Paint Color Node with Color Output.](../../../.gitbook/assets/getfillpaintcolornode.png)

The **Get Fill Paint Node** returns the value of the fill's `Paint Type` selected in the **Attributes**.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get Fill Paint Color Node Attributes.](../../../.gitbook/assets/getfillpaintcoloratts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|Can be either `Fill` or `Stroke`. In this case, `Fill` has been chosen.|
|`Index`|**Int**|Determines the layer of the fill content, if one is not provided in the **Input Socket**. It works in a top to bottom way, where 0 is the top layer and increasing layers are below it.|
|`Paint Type`|**Dropdown**|The type of `Fill` that was used on the inputted **Object**. The choices are `Color`, `Gradient`, `Image`, `Video`, and `Shader`. The first two result in a `Color` output, while the other three result in a `Texture ID` output.| 

## Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its fill returned.|
|`Index`|**Int**|The index of the fill’s layer.| 

## Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Color`|**Color

{% endtab %}

{% tab title="Stroke" %}


## Overview

![The Get Stroke Paint Color Node.](../../../.gitbook/assets/getstrokepaintcolor.png)

The **Set Paint Node** .

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

## Attributes

![The Get Stroke Paint Color Node Attributes.](../../../.gitbook/assets/getstrokepaintcoloratts.png)

|Attribute|Type|Description|
|---|---|---|

## Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

## Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|


{% endtab %}
{% endtabs %}

# See Also

# External Links

