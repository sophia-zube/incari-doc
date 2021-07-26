# Overview

![The Get Dictionary Values Node.](../../.gitbook/assets/get-dictionary-values.png))

The **Get Dictionary Values** **Node** takes a **Dictionary** as **Input** and yields its set of _values_. It also outputs the received **Dictionary**.


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Dictionary` | **Dictionary** | The **Dictionary** from which you wish to obtain the _values_.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Dictionary` | **Dictionary** | The **Dictionary** provided to the **Input** **Socket**. |
| `Values` | **Array** | An **Array** containing the _values_ from the given **Dictionary**.|

# See Also

* [Dictionary Value](dictionary-value.md)
* [Set Dictionary Element](set-dictionary-element.md)


