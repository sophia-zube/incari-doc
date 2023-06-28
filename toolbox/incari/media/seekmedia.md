# Seek Media

This **Node** can be used to seek a particular point of a **Media** **Object**. It has three different versions depending on the `Seek Mode` chosen. Find in the tabs below the documentation for all versions.


{% tabs %}
{% tab title="Frame" %}

# Overview

![The Seek Media Node, with `Seek Mode`: Frame.](../../../.gitbook/assets/node-seekmedia-frames.png)

The **Seek Media** **Node** with `Seek Mode`: `Frame` can be used to navigate to a particular point in a [**Video**](../../../objects-and-types/scene-objects/3dobjects/video.md) providing the corresponding timeframe as input.

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Seek Media Node Attributes.](../../../.gitbook/assets/node-node-seekmedia-attri.png)

|Attribute|Type|Description|
|---|---|---|
| `Seek Mode` | **Dropdown** | Mode for seeking the **Media** **Object**. In this case, `Frame`. Please note that the `Frame` `Seek Mode` only permits seeking **Video Objects** and it does not work for **Audio Objects**, for which one of the other `Seek Modes` has to be used.  |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | **ID** of the **Video** **Object** to be sought. |
| `Frame Number` | **Int** | *Frame number* to navigate to. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}
{% tab title="Percentage" %}
# Overview

![The Seek Media Node, with `Seek Mode`: Percentage.](../../../.gitbook/assets/node-seekmedia-percentage.png))

The **Seek Media** **Node** with `Seek Mode`: `Percentage` can be used to navigate to a particular point in a **Media Object** providing the corresponding percentage as input. **Media** in **Incari** is either a [**Video**](../../../objects-and-types/scene-objects/3dobjects/video.md) or an [**Audio**](../../../objects-and-types/scene-objects/audio.md). 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Seek Media Node Attributes.](../../../.gitbook/assets/node-node-seekmedia-attri.png)

|Attribute|Type|Description|
|---|---|---|
| `Seek Mode` | **Dropdown** | Mode for seeking the **Media** **Object**. In this case, `Percentage`. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | **ID** of the **Media** **Object** to be sought. |
| `Percentage` | **Float** | Percentage of the **Media Object** to navigate to. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

{% endtab %}

{% tab title="Seconds" %}
# Overview

![The Seek Media Node, with `Seek Mode`: Seconds.](../../../.gitbook/assets/node-seekmedia-seconds.png)

The **Seek Media** **Node** with `Seek Mode`: `Seconds` can be used to navigate to a particular point in a **Media Object** providing the corresponding second as input. **Media** in **Incari** is either a [**Video**](../../../objects-and-types/scene-objects/3dobjects/video.md) or an [**Audio**](../../../objects-and-types/scene-objects/audio.md). 

[**Scope**](../../overview.md#scopes): **Scene**, **Function**, **Prefab**.

# Attributes

![The Seek Media Node Attributes.](../../../.gitbook/assets/node-node-seekmedia-attri.png)

|Attribute|Type|Description|
|---|---|---|
| `Seek Mode` | **Dropdown** | Mode for seeking the **Media** **Object**. In this case, `Seconds`. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Object ID` | **ObjectID** | **ID** of the **Media** **Object** to be sought. |
| `Seconds` | **Dropdown** | Mode for seeking the **Media** **Object**

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
{% endtab %}
{% endtabs %}

# See Also

* [**Play Media**](playmedia.md)
* [**Stop Media**](stopmedia.md)


