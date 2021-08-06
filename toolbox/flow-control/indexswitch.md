# Overview

![The Index Switch Node.](../../.gitbook/assets/indexswitch.png)



The **Index Switch Node** takes an **Int** as input and compares it to the value of`Index: value`, returning true or false. This could be used for enabling or disabling features in a user interface based on the output of a function, for example.


# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Default Index`|**Dropdown**|The **Index** that corresponds to `Default`.|
|`Outputs`|**Dropdown**|The number of **Index** outputs. In the sample image there are two `Outputs`, which corresponds to `Index: 0` and `Index: 1` on the **Node**.|


# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Index`|**Int**|The **Integer** to be compared.|



# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`Index: 0`|**Bool**|The **Index** that is being compared to the **Integer** **Input**. Can continue with `Index: 1`, `Index: 2`, and so on.|
|`Default`|**Bool**|The default index which is set in **Inputs**.|


# External Links

