# Overview

![The CharCodeAt Node.](../../.gitbook/assets/node-charcodeat.png)

The **CharCodeAt** **Node** outputs the _ASCII_ code of a character at a given index in a **String**. It takes as inputs a **String** and the index of the character whose code is to be obtained, and it ouputs the _ASCII_ code if said character.

The indices of the characters in the **String** start from zero.

If the index given is greater than the length of the **String**, the output is `-1`.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `String` | **String** | The **String** from which the characters codes are to be obtained, if none is given in the **Input Socket**.  |
| `At` | **Int** | The index of the character whose _ASCII_ code is to be obtained, if none is given in the **Input Socket**.  |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `String` | **String** | The **String** from which the characters codes are to be obtained. |
| `At` | **Int** | The index of the character whose _ASCII_ code is to be obtained. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Char code` | **Int** | The _ASCII_ code of the character at position `At` in `String`.  |


# External Links

* [_ASCII_](https://en.wikipedia.org/wiki/ASCII) on Wikipedia.
* [_HTML ASCII Reference_](https://www.w3schools.com/charsets/ref_html_ascii.asp) on W3Schools.