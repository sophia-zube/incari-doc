# Set Current Index

## Overview

![The Set Current Index Node.](../../../.gitbook/assets/set-current-index.PNG)

**Set Current Index** selects an entry item by using its _index_. It accepts a **List** **Object** and an `Index` value and selects an entry item corresponding to the `Index` value.

The index count starts from zero, which means that the `Index` of the last entry item of the **List** **Object** is equal to the total number of entry items minus one \("sum of entries" - 1\). This follows from array-based indexing where the index of the first entry is 0.

## Attributes

### Object

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Object` | **ObjectID** | This represents the **List** **Object**, from which an entry item can be selected by its `Index`, if one is not provided in the `Object ID` **Socket**. |

### Input

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Index` | **Int** | The default `Index` value if no value is provided to the input `Index` **Socket**. |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Object ID` | **ObjectID** | The **List** **Object** from which an entry item can be selected by using its _index_. |
| `Index` | **Int** | The _index_ of the entry item you wish to select. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |

## See Also

* [**List**](../../../getting-started/scene-objects/list.md)
* [**Generate List**](generate-list.md)

## External Links

* [_Array Indexing_](https://en.wikipedia.org/wiki/Array_data_structure)
* [_Index Mapping_](https://en.wikipedia.org/wiki/Index_mapping)

