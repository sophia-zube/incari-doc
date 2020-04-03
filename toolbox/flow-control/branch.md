# Branch

## Overview

![](../../.gitbook/assets/branch-node.png)

Like a branch on a tree, the **Branch Node** splits a single path into two diverging paths. Which branch of logic is executed depends on a single condition, which can itself be composed of multiple conditions. At a high level it basically means "_If this is true, do this; if not, do this._" which sounds relatively simplistic, however, branching is a foundational concept of creating interactive logic, similar to using _if statements_ in programming, and when combined with **Relational Expression**, **Pulse Flow** and **Logical Operator** **Nodes**, we can build incredibly complex systems.

## Uses

There are infinite uses for the **Branch Node**, however a very basic example would be a single **Input** condition, which triggers one of two functions. In the example below we use a **Variable** to represent whether the unit of measurement for distance is set to _km/h_ or _mph_, and trigger functions to display data in the corresponding format.

![Basic example of the Branch node.](../../.gitbook/assets/branching-example-simple.png)

These _conditional statements_ can be chained together and combined with other **Nodes**. Below is an example where the **Logic** checks: 1. If the passenger seat is occupied. If it is \(_true_\) then... 2. It checks if the passenger seat belt is fastened. If it isn't \(_false_\) then... 3. It sounds an alarm.

![An intermediate example of the Branch node.](../../.gitbook/assets/branching-example-intermediate.png)

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `OnTrue` | **Pulse** | Triggers the execution of subsequent logic if **Input** condition is _True_. |
| `OnFalse` | **Pulse** | Triggers the execution of subsequent logic if **Input** condition is _False_. |

## External Links

* [_Condiitonal \(computer programming_](https://en.wikipedia.org/wiki/Conditional_%28computer_programming%29) on Wikipedia.

