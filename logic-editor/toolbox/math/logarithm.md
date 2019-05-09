# Overview

![](../../../.gitbook/assets/node-logarithm.png)

**Logarithm** performs the inverse function of the **Power Node**. Rather than taking a *base* **Value**, raising it to the power of an *exponent*, and returning the *power*, it takes the *base* **Value**, along with the *power*, and returns the *exponent*.

# Exponentiation-Related Nodes

The **Power**, **n<sup>th</sup> Root**, and **Logarithm** **Nodes** each relate to *exponentiation*. They all take two *known* parameters and return the 3<sup>rd</sup> *unknown* **Value**. 

![](../../../.gitbook/assets/exponential-functions.png)

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Base`|**Drop-down**|A selection of common bases used in logarithm functions, which are: `2` (binary), `e` (natural) or `10` (common).|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**|The *power* or *antilogarithm* to be used, along with the *base*.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Float**|The *logarithm* of the *base* and *antilogarithm*.|

# External Links

- [*Logarithmic Functions*](https://www.sparknotes.com/math/precalc/exponentialandlogarithmicfunctions/section2/) on sparknotes.