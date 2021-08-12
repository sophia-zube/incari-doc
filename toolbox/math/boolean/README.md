# Boolean

## Introduction

A **Boolean** is a _data type_, which represents one of two values: _true_ or _false_.

Although **Booleans** themselves are conceptually simple, and take up very little memory, they are an integral part of Incari's logic system, and computer programming in general, due to their use in **Flow Control**. More specifically, _Boolean expressions_ are used to define the conditions that determine what actions will be taken, dependent on whether they are evaluated as being _true_ or _false_.

## Boolean Value

The [**Boolean Value Node**](boolean-value.md) simply stores a **Boolean** value in its internal _state_, which can be defined before the **Project**'s execution and can be modified and retrieved at runtime.

## Logical Operator Nodes

_Logical operator_ **Nodes** combine two or more **Boolean** expressions to yield a **Boolean** value based on the inputs' logical relationship to one another. These are:

* [**AND**](and.md) - Returns _true_ if all of the **Node**'s inputs are also _true_. The equivalent of the `&&` operator in computer programming.
* [**OR**](or.md) - Returns _true_ if at least one of the **Node**'s inputs are _true_. The equivalent of the `||` operator in computer programming.

There is also the [**Negate Node**](negate.md), whose output is simply the **Boolean** value _opposite_ to its input. This is used to mean _NOT_ and is the equivalent of the `!` operator in computer programming.

## Contents

* [**Boolean Value**](boolean-value.md)
* [**AND**](and.md)
* [**Negate**](negate.md)
* [**OR**](or.md)

## External Links

* [_Logical operation_](https://www.computerhope.com/jargon/l/logioper.htm) on Computer Hope.

