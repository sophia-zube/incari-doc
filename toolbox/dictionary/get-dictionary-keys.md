# Get Dictionary Keys

## Overview

![The Get Dictionary Keys Node.](../../.gitbook/assets/get-dictionary-keys.png)

The **Get Dictionary Keys** **Node** takes a **Dictionary** as **Input** and yields its set of _keys_ as an **Array**. It also outputs the received **Dictionary**.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Dictionary` | **Dictionary** | The **Dictionary** from which you wish to obtain the _keys_. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Dictionary` | **Dictionary** | The **Dictionary** provided to the **Input** **Socket**. |
| `Keys` | **Array** | An **Array** containing the _keys_ from the given **Dictionary**. |

## See Also

* [Dictionary Value](dictionary-value.md)
* [Set Dictionary Element](https://github.com/cgi-studio-gmbh/incari-doc/tree/fd6a90829eb73ff4f340ca1436f6b3ac1e2e1cbf/toolbox/dictionary/set-dictionary-element.md)

