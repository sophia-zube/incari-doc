# Create CustomID

## Overview

![The Create CustomID Node.](../../.gitbook/assets/node-create-customid2.png)

Everything in **Incari** has a unique ID number, from **Assets** to **Nodes** to **Variables**. The **Create** **CustomID** Node creates a new unique ID.

This way, for example, the user can create a new ID for an **Animation Block** to differentiate between several **Play Animation Nodes**. This allows one to play different **Animations** simultaneously and have them appear as unique to each other within **Incari**. 

Furthermore, it is possible for the same **Object** to have multiple *instances*, thus resulting in different ID numbers for one **Object**. 

## Inputs

| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Output` | **CustomID** | A new, unique ID number. |

