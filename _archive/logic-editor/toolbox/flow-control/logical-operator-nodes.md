# Logical Operator Nodes

Logical operator nodes are used to combine Boolean expressions by checking the evaluation of multiple conditions.

## AND

![The AND node.](../../../.gitbook/assets/nodeand.png)

The **AND** node takes two **Boolean** values as input and returns a **Boolean**. It returns _true_ if both of its inputs are also _true_. If one or both of the inputs are _false_, the node returns _false_. 

| Input 1 | Input 2 | Output |
| :--- | :--- | :--- |
| True | True | True |
| True | False | False |
| False | True | False |
| False | False | False |

### Usage

![In the above example, a combination or relational nodes and the AND node, to check if a tire&apos;s pressure is within a given range.](../../../.gitbook/assets/andexample.png)

## OR

![The OR node.](../../../.gitbook/assets/nodeor.png)

The **AND** node takes two **Boolean** values as input and returns a **Boolean**. It returns _true_ if one or both of the inputs are _true_. The node only returns _false_ if both of its inputs are _false_. 

| Input 1 | Input 2 | Output |
| :--- | :--- | :--- |
| True | True | True |
| True | False | True |
| False | True | True |
| False | False | False |

### Usage

![The above example checks if either of the front car doors are open.](../../../.gitbook/assets/orexample.png)

## Negate

![The Negate node.](../../../.gitbook/assets/nodenegate.png)

The **Negate** node takes a single **Boolean** value as an input and returns its inverse. If the input is _true_, it returns _false_ and vice versa.

| Input | Output |
| :--- | :--- |
| True | False |
| False | True |



