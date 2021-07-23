# Overview

![The Erase Dictionary Element Node.](../../.gitbook/assets/erase-dictionary-value.PNG)

The **Erase Dictionary Element** removes an element or more of a **Dictionary**. It receives as input the **Dictionary** from which the element/s will be removed and the `key/s` of the element/s to erase.

# Attributes

## Inputs

`Inputs` - The number of elements you wish to remove from the **Input** **Dictionary**. Each element has the following **Attribute**:

|Attribute|Type|Description|
|---|---|---|
| `Key` | **String** | The `Key` of the element you wish to remove if none is given in the **Input** **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**| A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Dictionary` | **Dictionary** | The **Dictionary** from which you wish to remove elements. |
| `Index (*Key name*)` | **String** | The `Key name` of the element you wish to remove. | 

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Dictionary` | **Dictionary** | The resulting **Dictionary** after the desired elements were removed | 

# See Also

* [Clear Dictionary](clear-dictionary.md)
* [Set Dictionary Element](set-dictionary-element.md) 



