# Play Animation
<<<<<<< Updated upstream

Play Animation:

## Play Animation

### Overview

![The Play Animation Node.](../../../.gitbook/assets/playanimation.png) ![The Play Animation Node with input](../../../.gitbook/assets/playanimationwithfile.png)
=======
## Overview

<!--- ![The Play Animation Node.](../../../.gitbook/assets/playanimation.png)--->

<style>
.resizingimage {
  max-width: 75%;
}
</style>

<img src="../../../.gitbook/assets/playanimation.png" class="resizingimage" alt="The Play Animation Node">

The Play Animation Node.


<img src="../../../.gitbook/assets/playanimationwithfile.png" class="resizingimage" alt="The Play Animation Node with input.">

The Play Animation Node with input. 

<!---![The Play Animation Node with input.](../../../.gitbook/assets/playanimationwithfile.png)--->



**Play Animation** is an _animation_ **Node** used to play an **Animation** that can be used with **Pause Animation** and **Stop Animation**. Once an **Animation** is created in the **Animation Editor Module**, it can be selected in the file selector. A dropdown will appear that allows the user to choose an **Animation Block**. This will show up as a blue-colored input on the **Play Animation Node**.
>>>>>>> Stashed changes

**Play Animation** is an _animation_ **Node** that can be found under the _incari_ **Category**. This **Node** is used to play an **Animation** when the project is run and can be used in conjunction with **Pause Animation** and **Stop Animation**. Once an **Animation** is created in the **Animation Editor Module**, it can be selected in the file selector. A dropdown will appear that allows the user to choose an **Animation Block**. This will show up as a blue-colored input on the **Play Animation Node**.

### Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `File` | **User Input** | The selected **Animation** file created in the **Animation Editor**. The user can drag a file from their library or select a file from a file tree. The icons to the right allow the user to confirm the selection, highlight the **Asset** in the **Asset Manager**, and remove the selection. |
<<<<<<< Updated upstream
| `Name` | **Dropdown Menu** | The specified **Animation Block**. These are created in the **Animation Editor**. In the sample image, it is labeled **Animation Block**, but it is useful to name it in relation to the animation purpose. |
=======
|`Name`|**Dropdown Menu**|The specified **Animation Block** created in the **Animation Editor**. In the sample image, it is labeled **Animation Block**, but it is useful to name it in relation to the animation purpose.| 
>>>>>>> Stashed changes

### Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `InstanceID` | **InstanceID** | The assigned **Instance** of an **Animation Block**. |

### Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
<<<<<<< Updated upstream
| _InstanceID_ | **CustomID** | The previously assigned **Instance** of the **Animation Block**. |
| _OnPlay_ | **Pulse** | Flows to additional actions following **Play Animation** if the **Animation** is currently playing. |
| _OnPause_ | **Pulse** | Flows to additional actions following **Play Animation** if the animation pauses. |
| _OnStop_ | **Pulse** | Flows to additional actions following **Play Animation** if the animation ends. |

=======
| `InstanceID` | **InstanceID** | The previously assigned **Instance** of the **Animation Block**. |
| `OnPlay` | **Pulse** | Flows to additional actions following **Play Animation** if the **Animation** is currently playing. |
| `OnPause` | **Pulse** | Flows to additional actions following **Play Animation** if the animation pauses. |
| `OnStop` | **Pulse** | Flows to additional actions following **Play Animation** if the animation ends. |

## See Also 

* [**Pause Animation**](pauseanimation.md)
* [**Stop Animation**](stopanimation.md)
>>>>>>> Stashed changes
