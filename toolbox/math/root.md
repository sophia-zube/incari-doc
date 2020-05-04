# Overview

![](../../.gitbook/assets/node-root.png)

**Root** calculates the *nth root* of a number. This is effectively the reversal of the **Power** operation, meaning that instead of multiplying a *base* by itself, multiple times, it calculates what the base number is, based on how many times it was multiplied by itself.

The most common example of **Root** operations, is finding the *square* (degree 2) root, or *cubic* (degree 3) *root* of a number, however this can also be used for higher numbers.

|`Base`|`Degree`|`Output`|
|---|---|---|---|
|9|2|3|
|13824|3|24|
|160000|4|20|
|1024|10|2|

# Attributes

|Input|Type|Description|
|---|---|---|
|`Default Base`|**Float**|The default value of `Base`, if no value is provided in the `Base` **Socket**.|
|`Default Degree`|**Float**|The default value of `Degree`, if no value is provided in the `Degree` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Base`|**Float**|The value which you want to find the *nth root* of.|
|`Degree`|**Float**|The degree of the root.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|**Float**|The *nth root* (defined in `Degree`) of `Base`.|

# See Also
- [**Power**](power.md)

# External Links

- [*Root*](https://www.mathopenref.com/root.html) on Math Open Reference.
- [*nth root*](https://en.wikipedia.org/wiki/Nth_root) on Wikipedia.