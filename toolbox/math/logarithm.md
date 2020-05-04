# Overview

![](../../.gitbook/assets/node-logarithm.png)

**Logarithm** performs the inverse function of the **Power Node**. Rather than taking a *base* value, raising it to the power of an *exponent*, and returning the *power*, it takes the *base* Value, along with the *power*, and returns the *exponent*.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Base`|**Drop-down**|A selection of common bases used in logarithm functions, which are: `2` (binary), `e` (natural), or `10` (common), as well as a `Custom` option, for defining a custom *base* value.|
|`Custom` *(Made available by the `Base` **Attribute**)*|**Float**|A custom *base* value.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**|The *power* or *antilogarithm* to be used, along with the *base*.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|**Float**|The *logarithm* of the *base* and *antilogarithm*.|

# External Links

- [*Logarithmic Functions*](https://www.sparknotes.com/math/precalc/exponentialandlogarithmicfunctions/section2/) on sparknotes.