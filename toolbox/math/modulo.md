# Overview

![](../../.gitbook/assets/node-modulo.png)

**Modulo** is a *modular arithmetic* **Node**, which divides one number (*dividend*) by a second number (*divisor*) and outputs the *remainder* of the *Euclidean division* operation.

This is the equivalent of the modulo (`%`) operation in computer science.

|`Dividend`|`Divisor`|Quotient|`Remainder`|
|---|---|---|---|
|10|25|2|5|
|5.5|1.5|3|1|
|540|360|1|180|
|15|12|1|3|

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|**Drop-down**|The type of data that will be plugged into the `Input` **Sockets**.|
|`Default Dividend`|*Defined in the `Data Type` **Attribute***.|The left side of the *Euclidean division* operation (the number to be divided) if no value is provided in the `Dividend` **Socket**.|
|`Default Divisor`|*Defined in the `Data Type` **Attribute***.|The right side of the *Euclidean division* operation (the number to divide by) if no value is provided in the `Divisor` **Socket**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|
|`Dividend`|*Defined in the `Data Type` **Attribute***.|The left side of the  *Euclidean division* operation (the number to be divided).|
|`Divisor`|*Defined in the `Data Type` **Attribute***.|The right side of the *Euclidean division* operation (the number to divide by).|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`Remainder`|*Defined in the `Data Type` **Attribute**.*|The remainder of the *Euclidean division* operation.|


# External Links

- [*Intro to remainders*](https://www.khanacademy.org/math/arithmetic/arith-review-multiply-divide/arith-review-remainders/v/introduction-to-remainders) on Kahn Academy.
- [*What is modular arithmetic?*](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/what-is-modular-arithmetic) on Kahn Academy.
