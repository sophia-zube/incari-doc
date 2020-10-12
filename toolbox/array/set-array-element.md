# Set Array Element

## Overview

![The Set Array Element Node.](../../.gitbook/assets/set-array-element.PNG)

**Set Array Element** updates element/s in an **Array** to new values.

## Attributes

### Inputs

#### Inputs

The number of **Input Element**/s you wish to add to the **Attribute section**. The **Input Element**/s are used to update elements in the **Array** to new values. Each **Input Element** has the following format:

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Index` | **Int** | The default `Index` of the element you wish to update if no value is provided in the `Index` **Input** **Socket**. |
| `Data Type` | **Drop-down** | The `Data Type` of the `Index` element you wish to update. |
| `Default Value` | _Defined in the_ `Data Type` _**Attribute**_. | The element whose `Index` is specified in the `Index` **Attribute** will be updated with this value. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Àrray` | **Array** | An **Array** whose element/s you wish to update. |
| `Index` | **Int** | The `Index` of the element you wish to update. |
| `Value` | _Defined in the_ `Data Type` _**Attribute**_. | An **Input** value that is used to replace the element whose _index_ is specified in the `Index` **Input** **Socket**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Array` | **Array** | An **Output** **Array** whose element/s have been replaced with the desired values. |

## Eg Usage

![The Set Array Element Node Usage.](https://github.com/cgi-studio-gmbh/incari-doc/tree/66656c2442958de634bc73f77b533a03f83df0fb/.gitbook/assets/toolbox/array/set-array-element-Usage.png)

## See Also

* [**Array Value**](array-value.md)
* [**Pop Array Element**](pop-array-element.md)

