# Set Blend Mode

This **Node** has different versions based on whether `Fill`,`Stroke`, or `Object` is set in the **Attributes**.

{% tabs %}
{% tab title="Fill" %}
# Overview

![The Set Fill Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/setfillblendmode20241.png)

The **Set Fill Blend Mode Node** allows the user to change an **Object** fill’s *blend mode*. This is chosen in the **Attributes** with `Blend Mode`.



[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Set Fill Blend Mode Node Node Attributes.](../../../.gitbook/assets/setblendmodefillatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|The type of content that will have its *blend mode* changed. The options are `Fill`, `Stroke`, `Object`, and `Effect`. For this **Node**, `Fill` has been selected.|
|`Index`|**Int**|Determines the layer of the fill content, if one is not provided in the **Input Socket**. It works in a top to bottom way, where 0 is the top layer and increasing layers are below it. |
|`Blend Mode`|**Dropdown**|The desired *blend mode*. More information on these can be found [here](http://www.simplefilter.de/en/basics/mixmods.html). |


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its fill’s *blend mode* set.|
|`Index`|**Int**|The index of the fill’s layer.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}

{% tab title="Stroke" %}

# Overview

![The Set Stroke Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/setstrokeblendmode20241.png)

**Set Stroke Blend Mode Node** allows the user to change an **Object** stroke's *blend mode*. This is chosen in the **Attributes** with `Blend Mode`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Set Stroke Blend Mode Node Attributes.](../../../.gitbook/assets/setblendmodestrokeatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|The type of content that will have its *blend mode* changed. The options are `Fill`, `Stroke`, `Object`, and `Effect`. For this **Node**, `Stroke` has been selected.|
|`Index`|**Int**|Determines the layer of the stroke content, if one is not provided in the **Input Socket**. It works in a top to bottom way, where 0 is the top layer and increasing layers are below it. |
|`Blend Mode`|**Dropdown**|The desired *blend mode*. More information on these can be found [here](http://www.simplefilter.de/en/basics/mixmods.html).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its stroke's *blend mode* set.|
|`Index`|**Int**|The index of the stroke's layer.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}

{% tab title="Object" %}

# Overview

![The Set Object Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/setobjectblendmodenormal20241.png)

**Set Object Blend Mode Node** allows the user to change an **Object's** *blend mode*. This is chosen in the **Attributes** with `Blend Mode`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Set Object Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/setblendmodeobjectatts.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|The type of content that will have its *blend mode* changed. The options are `Fill`, `Stroke`, `Object`, and `Effect`. For this **Node**, `Object` has been selected.|
|`Blend Mode`|**Dropdown**|The desired *blend mode*. More information on these can be found [here](http://www.simplefilter.de/en/basics/mixmods.html).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its stroke's *blend mode* set.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|


{% endtab %}

{% tab title="Effect" %}

# Overview

![The Set Effect Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/seteffectblendmode20241.png)

**Set Effect Blend Mode Node** allows the user to change an **Object's** *blend mode*. This is chosen in the **Attributes** with `Blend Mode`.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Set Effect Blend Mode Node with Normal Blend Mode.](../../../.gitbook/assets/seteffectblendmodeatts20241.png)

|Attribute|Type|Description|
|---|---|---|
|`Target`|**Dropdown**|The type of content that will have its *blend mode* changed. The options are `Fill`, `Stroke`, `Object`, and `Effect`. For this **Node**, `Effect` has been selected.|
|`Blend Mode`|**Dropdown**|The desired *blend mode*. More information on these can be found [here](http://www.simplefilter.de/en/basics/mixmods.html).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Object ID`|**ObjectID**|The ID of the **Object** that will have its stroke's *blend mode* set.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|


{% endtab %}
{% endtabs %}


# External Links

* More on blend modes [*here*](http://www.simplefilter.de/en/basics/mixmods.html)

