# Overview

![](../../.gitbook/assets/node-is-less-equal.png)

**Is Less Equal** is a *relational expression* **Node**, which compares two input values, and returns a **Boolean**, based on how the two values compare to each other in terms of *inequality*. The **Node** has two modes, determined by the `Mode` **Attribute**:

1. `IsLess` - Whether the value of `A` is less than the value of `B`.
2. `IsLessEqual` - Whether the value of `A` is less than *or* equal to the value of `B`.

*Relational expressions* are frequently used in combination with **Branch Nodes** and *logical operator* **Nodes** (**AND**, **OR**, and **Negate**) to create *conditional logic*, and are essential for building complex systems.

Due to their nature, *inequality* operations only work for *numerical data types*.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `A` and `B` **Sockets**.|
|`Mode`|**Drop-down**|The type of expression that will be used when comparing the values.|
|`Default Value A`|*Defined in the* `Data Type` ***Attribute***.|The value of `A` if no value is provided via the **Node**'s **Socket**.|
|`Default Value B`|*Defined in the* `Data Type` ***Attribute***.|The value of `B` if no value is provided via the **Node**'s **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`A`|*Defined in the* `Data Type` ***Attribute**.*|The **Value** to be compared with `B`.|
|`B`|*Defined in the* `Data Type` ***Attribute**.*|The **Value** to be compared with `A`.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`C`|**Bool**|Returns *true* if the value of `A` is less than (or equal to, depending on `Mode`) to `B`. If not, then it returns *false*.|

# External Links

[*Relational operator*](https://en.wikipedia.org/wiki/Relational_operator) on Wikipedia.