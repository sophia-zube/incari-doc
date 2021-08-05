# Index Switch

# Overview

![The Index Switch Node.](../../.gitbook/assets/indexswitch.png)

The **Index Switch Node**.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Default Index`|**Dropdown**|The **Index** that corresponds to `Default`.|
|`Outputs`|**Dropdown**|The number of **Index** outputs. In the sample image there are 2 `Outputs`, which corresponds to `Index: 0` and `Index: 1` on the **Node**.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Index`|**Int**| |

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Index: 0`|**Bool**|The **Index** that is being compared to the **Integer** **Input**. Can continue with `Index: 1`, `Index: 2`, and so on.|
|`Default`|**Bool**|The default index which is set in **Inputs**.|

# See Also

# External Links

