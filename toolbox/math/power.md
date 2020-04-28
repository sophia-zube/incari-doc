# Overview

![](../../.gitbook/assets/node-power.png)

**Power** performs an *exponentiation operation*, meaning that it multiplies the `Base` value, against itself, *n* times, with *n* being defined by `Exponent`.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Base` and `Input` **Sockets**.|
|`Default Base`|*Defined in the `Data Type` **Attribute***.|The default value of `Base`, if no value is provided in the `Base` **Socket**.|
|`Default Exponent`|*Defined in the `Data Type` **Attribute***.|The default value of `Exponent`, if no value is provided in the `Exponent` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Base`|*Defined in the `Data Type` **Attribute***.|The base value, that will be multiplied against itself multiple times, based on the `Exponent`. |
|`Exponent`|*Defined in the `Data Type` **Attribute***.|The number of times, the `Base` value will be multiplied against itself.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Output`|*Defined in the `Data Type` **Attribute***.|The result of the *exponentiation operation*.|

# See Also

- [**Root**](root.md)

# External Links

- [*Exponentiation: Definition & Examples*](https://study.com/academy/lesson/exponentiation-definition-examples-quiz.html) on Study.com.
- [*Exponentiation*](https://en.wikipedia.org/wiki/Exponentiation) on Wikipedia.