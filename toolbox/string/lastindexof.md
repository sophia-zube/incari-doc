# Overview

![The LastIndexOf Node.](../../.gitbook/assets/lastindexofnode.png)

The **LastIndexOf** **Node** returns the index of the last occurrence of a *substring* in a **String** and a **Bool** indicating whether it was found or not.

The range in which the *substring* will be searched can be customized via the `StartIndex` and `EndIndex` **Attributes**.

[**Scope**](../overview.md#scopes):
*  **Project**, **Scene**, **Function**, **Prefab**


# Attributes

![The LastIndexOf Node Attributes.](../../.gitbook/assets/lastindexofattributes.png)

|Attribute|Type|Description|
|---|---|---|
| `String` | **String** | The **String** in which the search will be performed. |
| `Pattern` | **String** | The *substring* that will be searched for. |
| `StartIndex` | **Int** | The *index* of `String` in which the search will start. |
| `EndIndex` | **Int** | The *index* of `String` in which the search will end. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `String` | **String** | The **String** in which the search will be performed. |
| `Pattern` | **String** | The *substring* that will be searched for. |
| `StartIndex` | **Int** | The *index* of `String` in which the search will start. |
| `EndIndex` | **Int** | The *index* of `String` in which the search will end. |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
| `LastIndexOf` | **Int** | The *index* of the last occurrence of `Pattern` in `String`.  |
| `Found` | **Bool** | Whether `Pattern` was found in `String` or not. |

# See Also

* [**IndexOf**](indexof.md)

# External Links

* [*Substring*](https://en.wikipedia.org/wiki/Substring) on Wikipedia.