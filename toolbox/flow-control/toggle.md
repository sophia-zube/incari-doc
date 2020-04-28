# Overview

![](../../.gitbook/assets/node-toggle.png)

Holds a **Boolean** *state*, which alternates between *true* and *false* every time the input **Pulse** is triggered. This can be thought of as being like a light switch, which alternates a light bulb's state between being *on* and *off*. 

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Value`|**Bool**|The default value/*state* of the **Node**, before it is executed.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard input **Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard output **Pulse**, to move onto the next **Node** along the *logic branch*, once this **Node** has finished its execution.|
|`is On`|**Bool**|Whether or not the value/*state* of the **Node** is currently  *true*.|

# External Links

- [*State*](https://www.techopedia.com/definition/696/state-computer-science) on Technopedia.