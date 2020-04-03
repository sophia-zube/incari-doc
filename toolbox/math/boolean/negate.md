# Negate

## Overview

The **Negate** node takes a _single_ **Boolean Value** and returns its inverse. If `Input` is _true_, it returns _false_ and vice versa.

It is commonly used along with **Branch** and _logical operator_ **Nodes** like **AND** and **OR**. In this case it can be thought of as meaning **NOT**.

| Input | Output |
| :--- | :--- |
| True | False |
| False | True |

## Attributes

_The **Negate Node** has no **Attributes**_.

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
| `Input [n]` | **Bool** | The **Value** to be inversed. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **Bool** | The inverse of `Input`. |

