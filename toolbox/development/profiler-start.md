# Overview

![The Profiler Start Node.](../../.gitbook/assets/node-profiler-start.png)

The **Profiler Start** **Node** marks the start of a **Profiler Block** that will be analyzed in the **Profiler View**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
| `Block Name` | **String** | Default name that the block will have in the **Profiler View**, if none is given in the **Input** **Socket**. |
| `Block Color` | **Color** | Color that the block will have in the **Profiler View**. |

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**| A standard **Input Pulse**, to trigger the execution of the **Node**.|
| `Block Name` | **String** | Name that the block will have in the **Profiler View**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Profiler Stop**](profiler-stop.md)
* [**Profiler View**](../../modules/profiler-view.md)



