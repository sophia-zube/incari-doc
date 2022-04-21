# Get LabelText

## Overview

![The Get LabelText Node.](../../../../.gitbook/assets/node-get-labeltext.png)

The **Get LabelText Node** returns the **LabelText** of a **Label Object** created in the **Scene Outliner Module** under **Vector**.

## Attributes

![The Get LabelText Node Attributes.](../../../../.gitbook/assets/node-get-labeltext-attr.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The target **Object**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the target **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `LabelText` | **String** | The **LabelText** of the target **Object**. |

