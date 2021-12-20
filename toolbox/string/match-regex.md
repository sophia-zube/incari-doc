# Overview

![The MatchRegex Node.](../../.gitbook/assets/node-matchregex.png)

**MatchRegex** .

# Attributes

## Inputs

|Attribute|Type|Description|
|---|---|---|
| `String` | **String** | |
| `Pattern` | **String** | |
| `From` | **Int** | |
| `To` | **Int** | |
| `Count all matches` | **Bool** | |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `String` | **String** | |
| `Regex` | **String** | |
| `From` | **Int** | |
| `To` | **Int** | |
| `Count all matches` | **Bool** |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `Found` | **Bool** | |
| `Position` | **Int** | |
| `Match count` | **Int** |

# See Also

* [**ReplaceRegex**](replaceregex.md)

# External Links

* [*Regular expression*](https://en.wikipedia.org/wiki/Regular_expression) on Wikipedia.

