# Overview

![](../../.gitbook/assets/node-modulo.png)

**Modulo** takes two **Numerical Type Inputs**; `a` \(_the dividend_\) and `b` \(_the divisor_\) and returns the _remainder_ of the *division* of `a` and `b`.

Unlike normal division, this kind of operation, actually considers how many times the divisor fits into the dividend in its entirity (the *quotient*), with the *remainder* being the amount that is left over.

|Dividend (`a`)|Divisor (`b`)|Quotient|Remainder (`c`)|
|---|---|---|---|
|10|25|2|5|
|5.5|1.5|3|1|
|540|360|1|180|
|15|12|1|3|

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Data Type`|*Defined in the* `Data Type` ***Attribute**.*|The **Numerical Data Type** of both the dividend and the divisor (`a` and `b`)|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`a`|*Defined in the* `Data Type` ***Attribute**.*|The dividend (number to be divided).|
|`b`|*Defined in the* `Data Type` ***Attribute**.*|The divisor (amount the dividend should be divided by).|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`c`|*Defined in the* `Data Type` ***Attribute**.*|The remainder of the division operation. (*divisor - dividend * quotient*).|


# External Links

- [*Intro to remainders*](https://www.khanacademy.org/math/arithmetic/arith-review-multiply-divide/arith-review-remainders/v/introduction-to-remainders) on Kahn Academy.
- [*What is modular arithmetic?*](https://www.khanacademy.org/computing/computer-science/cryptography/modarithmetic/a/what-is-modular-arithmetic) on Kahn Academy.
