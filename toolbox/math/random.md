# Overview

![The Random Node.](../../.gitbook/assets/node-random.png)

The **Random** **Node** generates a random number.

This **Node** can be set to three different `Modes` (**Advanced**, **Expert**, and **Standard**). Each of these `Modes` offers a different set of **Attributes** that are explained below.

# Attributes

Each `Mode` has a different set of **Attributes**. The `Modes` are: [**Advanced**](random.md#advanced), [**Expert**](random.md#expert), and [**Standard**](random.md#expert).

## Advanced

### Generator

|Attribute|Type|Description|
|---|---|---|
| `Is deterministic` | **Bool** | Whether the random number generator is deterministic or not. |
| `Seed` | **Int** (*only available when `Is Deterministic` is set to _true_*)| The `Seed` to use for the deterministic random number generator. |

### Distribution

This **Attribute** has a **Drop-down** menu from which the _probability distribution_ used for the random number generator can be chosen. Each option offers then its own set of **Attributes**, which are detailed below.

|Attribute|Type|Description|
|---|---|---|
| `Distribution` | **Drop-down** | The _probability distribution_ that the random number generator will use. |

* #### Bernoulli

|Attribute|Type|Description|
|---|---|---|
| `Probability of 'true'` | **Float** | |
* #### Binomial

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | |
| `Probability of 'true'` | **Float** | |
| `Number of trials` | **Int** | |
* #### Normal

|Attribute|Type|Description|
|---|---|---|
| `Mean` | **Float** | |
| `Standard deviation` | **Float** | |
* #### Poisson

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | |
| `Mean` | **Float** | |
* #### Uniform

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|




## Expert 

### Generator

|Attribute|Type|Description|
|---|---|---|
| `Generator` | **Drop-down** | |
| `Seed` | **Int** (*not available for non_deterministic `Generator`*) | The `Seed` to use for the deterministic random number generator. |

### Distribution

|Attribute|Type|Description|
|---|---|---|
| `Distribution` | **Drop-down** | |
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|
## Standard

### Distribution

|Attribute|Type|Description|
|---|---|---|
| `Data Type` | **Drop-down** | Whether an **Int**, **Float**, or **Byte** will be generated. |
| `Minimum` | _Defined in the `Data Type` **Attribute**_ | The lower bound of the interval from which the random number will be extracted.|
| `Maximum` | _Defined in the `Data Type` **Attribute**_ | The upper bound of the interval from which the random number will be extracted.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Output` | _Defined in the `Data Type` **Attribute**_ | The random number that was generated. |


# External Links

