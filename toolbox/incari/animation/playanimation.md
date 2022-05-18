# Play Animation

## Overview

![The Play Animation Node.](../../../.gitbook/assets/node-play-animation.png)

<!-- ![The Play Animation Block Node.](../../../.gitbook/assets/playanimationwithfile.png) -->

**Play Animation** is an **Animation** **Node** used to start playing an **Animation**. The **Animation** to play has to be selected in the **Attributes**. For this, simply drag an **Animation** `.incani` file from the **Asset Manager** to the `File` **Attribute** and then a drop-down Menu that allows the user to choose an **Animation Block** will appear.

When an **Animation** starts playing, an [**Instance ID**](README.md#instance-id) gets assigned to it, which is then used to control the **Animation** with the [**Pause Animation**](pauseanimation.md) or [**Stop Animation**](stopanimation.md) **Nodes**. This [**Instance ID**](README.md#instance-id) can be set with the [**Create CustomID Node**](../../utilities/createcustomid.md) connected to the `Instance ID` **Input Socket**. If nothing is connected, the default value 42 is used.

### Attributes

![The Play Animation Node Attributes.](../../../.gitbook/assets/node-play-animation-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `File` | **User Input** | The selected **Animation** file created in the [**Animation Editor**](../../../modules/animation-editor.md). The user can drag a file from their library or select a file from a file tree. The icons to the right allow the user to confirm the selection, highlight the **Asset** in the **Asset Manager**, and remove the selection. |
| `Name` | **Drop-down** | The specified **Animation Block** created in the **Animation Editor** that will be played. <!-- In the sample image, it is labeled **Animation Block**, but it is useful to name it in relation to the animation purpose. --> |

### Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Instance ID` | **InstanceID** | The assigned [**Instance ID**](README.md#instance-id) of the **Animation**. |

### Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Instance ID` | **InstanceID** | The previously assigned [**Instance ID**](README.md#instance-id) of the **Animation**. |
| `OnPlay` | **Pulse** | Flows to additional **Nodes** following **Play Animation** when the **Animation** starts playing. |
| `OnPause` | **Pulse** | Flows to additional **Nodes** following **Play Animation** if the **Animation** pauses. |
| `OnStop` | **Pulse** | Flows to additional **Nodes** following **Play Animation** if the **Animation** stops. |

## See Also

* [**Pause Animation**](pauseanimation.md)
* [**Stop Animation**](stopanimation.md)

