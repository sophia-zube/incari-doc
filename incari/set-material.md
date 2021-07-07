# Set Material

## Overview

![The Set Material Node.](../.gitbook/assets/set-material.PNG)

**Set Material** assigns a **Material** to an **Mesh** **Object**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | The **Object** which the **Material** is to be applied to if one is not provided in the `Object ID` **Socket**. |
| `Default Material` | **MaterialID** | The default value of the `Material` **Socket**, if no value is provided. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The ID of the **Mesh Object** that you would like to assign the **Material** to. |
| `Material` | **CustomID** | The **Material** to be applied to the **Mesh** **Object**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**Get Material**](get-material.md)

