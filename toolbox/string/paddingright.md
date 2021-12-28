# Overview

![The PaddingRight Node.](../../.gitbook/assets/node-paddingright.png)

The **PaddingLeft** **Node** adds a character a chosen number of times to the right of a **String**.

For example, padding the character "a" 6 times to the **String** "bbbbbbcccccc" gives as result "bbbbbbccccccaaaaaa".

The `Padding character` **Attribute** and **Input** can receive a **String** but they only use the first character.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `String` | **String** | The **String** to which the `Padding character` will be added on the right, if none is given in the **Input Socket**. |
| `Padding character` | **String** | The character that will be added on the left of `String`, if none is given in the **Input Socket**. |
| `Padding size` | **Int** | The number of times that the `Padding character` will be repeated, if none is given in the **Input Socket**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `String` | **String** | The **String** to which the `Padding character` will be added on the right. |
| `Padding char.` | **String** | The character that will be added on the left of `String`. |
| `Padding size` | **Int** | The number of times that the `Padding character` will be repeated.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Padded left` | **String** | The resulting **String** with the character padded on the right. |

# See Also

* [**PaddingLeft**](paddingleft.md)

