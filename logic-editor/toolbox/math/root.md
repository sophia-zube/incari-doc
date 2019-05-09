# Overview

![](../../../.gitbook/assets/node-root.png)

**Root** calculates the *nth root* of a number. The *nth root* (`Output`) of a number is the *base* value, which when raised to the power of *n* (`Degree`) would return the *radicand* (`Input`).

The most common example of **Root** operations, is finding the square (2nd) root, or cubic (3rd) root of a number, however this can also be used for higher numbers.

|`Input`|`Degree`|`Output`|
|---|---|---|---|
|9|2|3|
|13824|3|24|
|160000|4|20|
|1024|10|2|

# Attributes

*The **Root Node** has no **Attributes***.

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Input`|**Float**|The **Value** which you want to find the *nth root* of.|
|`Root`|**Float**|The degree of the exponentiation (the "*n*" in "*nth root*").|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Output`|**Float**|The *base* number which, when multiplied against itself the number of times defined in `Root`, would return the **Value** of `Input`. |

# External Links

- [*Root*](https://www.mathopenref.com/root.html) on Math Open Reference.
- [*nth root*](https://en.wikipedia.org/wiki/Nth_root) on Wikipedia.