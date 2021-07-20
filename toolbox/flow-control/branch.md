# Branch

## Overview

![The Branch Node.](../../.gitbook/assets/node-branch.png)

**Branch** triggers one of two **Pulses**, based on whether or not the `Input` value is _true_ or _false_. Branching is a fundamental part of _conditional logic_ and at a high level it basically means "_If this is true, do this; if not, do this_". Although the **Node** takes a single condition, this condition can be composed of multiple other conditions when used in conjunction with _relational expression_ **Nodes** \([**Is Equal**](https://docs.incari.com/incari-studio/toolbox/flow-control/is-equal), [**Is Greater Equal**](https://docs.incari.com/incari-studio/toolbox/flow-control/is-greater-equal), and [**Is Less Equal**](https://docs.incari.com/incari-studio/toolbox/flow-control/is-less-equal)\), _logical operator_ **Nodes** \([**AND**](https://docs.incari.com/incari-studio/toolbox/math/boolean/and), [**OR**](https://docs.incari.com/incari-studio/toolbox/math/boolean/or), and [**Negate**](https://docs.incari.com/incari-studio/toolbox/math/boolean/negate)\), and other **Branch Nodes**.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Default Value` | **Bool** | The default value if one is not provided in the `Input` **Input Socket.** |

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard input **Pulse**, to trigger the execution of the **Node**. |
| `Input` | **Bool** | The _true_ or _false_ condition to determine which of the two output **Pulses** is executed. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `OnTrue` \(►\) | **Pulse** | The **Pulse** that will be triggered if `Input` is _true_. |
| `OnFalse` \(►\) | **Pulse** | The **Pulse** that will be triggered if `Input` is _false_. |

## External Links

* [_Conditional \(computer programming\)_](https://en.wikipedia.org/wiki/Conditional_%28computer_programming%29) on Wikipedia.

