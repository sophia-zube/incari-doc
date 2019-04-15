# Overview

![](../../../.gitbook/assets/branch-node.png)

Like a branch on a tree, the **Branch Node** splits a single path into two diverging paths. Which branch of logic is executed depends on a single condition, which can itself be composed of multiple conditions. At a high level it basically means "_If this is true, do this; if not, do this._" which sounds relatively simplistic, however, branching is a foundational concept of creating interactive logic, similar to using _if statements_ in programming, and when combined with **Relational Expression**, **Pulse Flow** and **Logical Operator** **Nodes**, we can build incredibly complex systems.

# Uses

There are infinite uses for the **Branch Node**, however a very basic example would be a single input condition, which triggers one of two functions. In the example below we use a **Variable** to represent whether the unit of measurement for distance is set to _km/h_ or _mph_, and trigger functions to display data in the corresponding format.

![Basic example of the Branch node.](../../../.gitbook/assets/branching-example-simple.png)

By utilising various other nodes, we can define logical outcomes based on multiple conditions. In the example below we have four **Variables**, representing whether or not each of four car doors are open. By using the **Logical Operator Node**, **OR**, and triggering them all using a **Sequential Node**, we can trigger an alarm if any of the doors are open.

![An intermediate example of the Branch node.](../../../.gitbook/assets/branching-example-intermediate.png)

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|OnTrue|**Pulse**|Triggers the execution of subsequent logic if **Input** condition is _True_.|
|OnFalse|**Pulse**|Triggers the execution of subsequent logic if **Input** condition is _False_.|

# External Links

- [*Condiitonal (computer programming*](https://en.wikipedia.org/wiki/Conditional_\(computer_programming\)) on Wikipedia.