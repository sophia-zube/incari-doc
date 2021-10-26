# Overview

![The Replace Regex  Node.]()

The **Replace Regex** **Node** allows to replace parts of a **String** using regular expressions to search for the pattern to replace.

It receives three inputs:

* `String`: The **String** in which some parts will be replaced.
* `From`: The pattern, using regular expressions, that will be searched for and replaced.
* `To`: The **String** that will replaced the pattern defined in `From`.
  
For example, if the inputs are: `String`=`ababab`, `From`=`a`, and `To`=`C`; the output will be `Result`=`CbCbCb`.

# Attributes

|Attribute|Type|Description|
|---|---|---|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|

# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|

# See Also

* [**Replace**](replace.md)

# External Links

