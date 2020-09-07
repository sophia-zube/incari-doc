# Introduction

A **Boolean** is a *data type*, which represents one of two values: *true* or *false*.

Although **Booleans** themselves are conceptually simple, and take up very little memory, they are an integral part of Incari's logic system, and computer programming in general, due to their use in **Flow Control**. More specifically, *Boolean expressions* are used to define the conditions that determine what actions will be taken, dependent on whether they are evaluated as being *true* or *false*.

# Boolean Value

The [**Boolean Value Node**](boolean-value.md) simply stores a **Boolean** value in its internal *state*, which can be defined before the **Project**'s execution and can be modified and retrieved at runtime.

# Logical Operator Nodes 

*Logical operator* **Nodes** combine two or more **Boolean** expressions to yield a **Boolean** value based on the inputs' logical relationship to one another. These are:

* [**AND**](and.md) - Returns *true* if all of the **Node**'s inputs are also *true*. The equivalent of the `&&` operator in computer programming.
* [**OR**](or.md) - Returns *true* if at least one of the **Node**'s inputs are *true*. The equivalent of the `||` operator in computer programming.

There is also the [**Negate Node**](negate.md), whose output is simply the **Boolean** value *opposite* to its input. This is used to mean *NOT* and is the equivalent of the `!` operator in computer programming. 

# Contents
- [**Boolean Value**](boolean-value.md)
- [**AND**](and.md)
- [**Negate**](negate.md)
- [**OR**](or.md)

# External Links
- [*Logical operation*](https://www.computerhope.com/jargon/l/logioper.htm) on Computer Hope.