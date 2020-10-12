# Pop Array Element

## Overview

![The Pop Array Element Node.](../../.gitbook/assets/pop-array-element.PNG)

**Pop Array Element** removes element/s from an **Array** supplied to the **Node**. The element/s can be removed from either the _front_ or _back_ of the **Array**.

## Attributes

### Outputs

#### Outputs

The number of **Output** **Elements** you wish to add to the **Attribute** section. The **Elements** added will be removed from the **Input** **Array**. Each **Element** has the following format:

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Data Type` | **Drop-down** | The `Data Type` of the element you wish to remove from **Array**. |

### Mode

The `Mode` is a _toggle_ what determines if an element will be removed from the _front_ or _back_ of the **Array**.

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Pop end` | **Bool** | If the _toggle_ is switched on, the desired element is removed from the _back_ of the **Array** otherwise it will be removed from the _front_ of the **Array**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Array` | **Array** | The **Array** whose element you wish to remove. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Array` | **Array** | The resulting **Array** after the desired element/s are removed. |
| `Value` | _Defined in the_ `Data Type` _**Attribute**_. | The element removed from the **Array**. |

## See Also

* [**Array Value**](array-value.md)
* [**Push Array Element**](push-array-element.md)

