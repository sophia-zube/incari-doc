# Flow Control

## Overview

**Flow Control Nodes** are used to define the order in which the **Logic** is evaluated, allow a program to consider multiple conditions, and perform different actions based on those variable conditions.

**Nodes** in the **Flow Control** category fall into two subcategories:

* \*\*\*\*[_**Relational Expression**_ **Nodes**](https://docs.incari.com/incari-studio/toolbox/flow-control#relational-expression-nodes)
* [**Pulse Flow Nodes**](https://docs.incari.com/incari-studio/toolbox/flow-control#pulse-flow-nodes)

## Relational Expression Nodes

_**Relational Expression**_ **Nodes** compare two values and yield a value based on the relationship between those inputs. These include the following:

* [**IsEqual**](is-equal.md) - Compares whether two values are _equal_, or _not equal_, depending on `Mode`. This is the equivalent of the `==` and `!=` operators in computer programming.
* [**IsGreaterEqual**](is-greater-equal.md) - Compares whether one value is _greater_ than another, or if they are equal, depending on `Mode`. This is the equivalent of the `>` and `>=` operators in computer programming.
* [**IsLessEqual**](is-less-equal.md) - Compares whether one value is _less_ than another, or if they are equal, depending on `Mode`. This is the equivalent of the `<` and `<=` operators in computer programming.

## Pulse Flow Nodes

**Pulse Flow Nodes** are mainly used to change the _control flow_ of **Logic**, which means executing different **Logic Branches** based on various _conditions_. To achieve truly dynamic programs, they are used in synergy with _**Relational Expression**_ and _**Logical Operator**_ **Nodes**.

* [**Branch**](branch.md) - Takes one of two paths based on its input **Boolean** value. Similar to an `if` statement in computer programming.
* [**Switch**](switch.md) - Takes one of several paths if the input value is equal to a path's corresponding, pre-defined value. If not, then the `Default` path is taken. Similar to a `switch` statement in computer programming.
* [**Toggle**](toggle.md) - Holds a **Boolean** _state_, which alternates between its opposite state every time the input **Pulse** is triggered.
* [**Select Data**](select-data.md) - Takes two or more pairs of **Pulse** and **Data** inputs and outputs the value corresponding to the input **Pulse** that the **Node** was executed by. This is a useful way to converge **Pulse Flow** into a single path.

Additionally, **Incari** has the [**Sequential Node**](sequential.md), which triggers all output **Pulses** sequentially and is used primarily as a means of grouping and organizing blocks of **Logic** with a similar or combined purpose into a more visually readable way.

## See Also

* [**Boolean**](../math/boolean/)

## External Links

* [_Control Flow_](https://www.computerhope.com/jargon/c/contflow.htm) on Computer Hope.
* [_Conditional Statement_](https://www.computerhope.com/jargon/c/contstat.htm) on Computer Hope.
* [_Logical Operation_](https://www.computerhope.com/jargon/l/logioper.htm) on Computer Hope.
* [_State_](https://www.techopedia.com/definition/696/state-computer-science) on Technopedia.

