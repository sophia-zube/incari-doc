# Get Dictionary Values

## Overview

![The Get Dictionary Values Node.](../../.gitbook/assets/get-dictionary-values.png)

The **Get Dictionary Values** **Node** takes a **Dictionary** as **Input** and yields its set of _values_. It also outputs the received **Dictionary**.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Dictionary` | **Dictionary** | The **Dictionary** from which you wish to obtain the _values_. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Dictionary` | **Dictionary** | The **Dictionary** provided to the **Input** **Socket**. |
| `Values` | **Array** | An **Array** containing the _values_ from the given **Dictionary**. |

## See Also

* [Dictionary Value](dictionary-value.md)
* [Set Dictionary Element](https://github.com/cgi-studio-gmbh/incari-doc/tree/0c262d46ee6be19347933e2d39522aff52ab8c49/toolbox/dictionary/set-dictionary-element.md)

