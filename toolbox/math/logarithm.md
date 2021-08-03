# Overview

![The Logarithm Node.](../../.gitbook/assets/node-logarithm.png)

**Logarithm** calculates the _logarithm_ of a number in a chosen base. 

This is the inverse function of the [**Power Node**](power.md). Rather than taking a *base* value, raising it to the power of an *exponent*, and returning the *power*, it takes the *base* Value, along with the *power*, and returns the *exponent*.

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
|`Base`|**Drop-down**|A selection of common bases used in logarithm functions, which are: `2` (binary), `e` (natural), or `10` (common), as well as a `Custom` option, for defining a custom *base* value.|

## Default

|Attribute|Type|Description|
|---|---|---|
|`Base Value` *(Made available by the `Base` **Attribute** set to `Custom`)*|**Float**|A custom *base* value.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**| The number whose logarithm you wish to calculate.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Float**|The *logarithm* of `Input` in the chosen *base*.|

# External Links

- [*Logarithmic Functions*](https://www.sparknotes.com/math/precalc/exponentialandlogarithmicfunctions/section2/) on sparknotes.