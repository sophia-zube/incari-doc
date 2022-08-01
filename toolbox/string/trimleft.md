# Overview

![The TrimLeft Node.](../../.gitbook/assets/trimleft.png)

The **TrimLeft** **Node** trims certain chosen characters from the left side of a **String**, until a different character is found. It receives as **Input** a **String** to be trimmed and the characters to trim, and it outputs the trimmed **String**.

For example, trimming the characters "ab" from the **String** "babbaacababa" results in the trimmed **String** "cababa".

*Scope*: **Project**, **Scene**, **Function**, **Prefab**

# Attributes

![The TrimLeft Node Attributes.](../../.gitbook/assets/trimleftattributes.png)

|Attribute|Type|Description|
|---|---|---|
| `String`| **String** | The **String** to be trimmed from the left, if none is given in the **Input** **Socket**. |
| `Characters` | **String** | The characters to be trimmed from `String`, if none are given in the **Input Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `String` | **String** | The **String** to be trimmed from the left.|
| `Characters` | **String** | The characters to be trimmed from `String`. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Trimmed` | **String** | The trimmed **String**. |

# See Also

* [**TrimRight**](trimright.md)
* [**Trim**](trim.md)


