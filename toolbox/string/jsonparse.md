# JSON Parse

## Overview

![The JSON Parse Node.](../../.gitbook/assets/jsonparse.png)

**JSON Parse** allows the user to access the values of a *JSON* file in an **Array** format. Sometimes a **Node** already converts a *JSON* file into a **String**, such as **HTTP Get**, which prepares the data sufficiently for the `Input`. However, this is not always the case and sometimes **Load File** must be used first. Then that output can be used as the `Input`. Alternatively, a *JSON* file text can be typed into the `Value` section.

## Attributes
| Attribute | Type | Description |
| :--- | :--- | :--- |
|`Value`|**User Input**|A place to paste or type a *JSON* file's text.|
## Inputs
| Input | Type | Description |
| :--- | :--- | :--- |
| _Pulse Input_ \(►\) | **Pulse** | A standard **Input Pulse**, to trigger the execution of the **Node**. |
|`Input`|**String**|The *JSON* file (in **String** format) to parse.|

## Outputs
| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
|`Output`|**Any**|The parsed key/value pairs of the *JSON* file that can now be accessed as an **Array**. For a different **Data Type**, such as a **Dictionary**, the **Conversion Node** must be used first.|
|`IsArray`|**Bool**|Returns true or false whether or not the parsed output is an **Array**.|


## See Also

* [**JSON Stringify**](jsonstringify.md)
* [**Load File**](../io/loadfile.md)
* [**Using APIs to Pull Dynamic Data**](https://docs.incari.com/incari-studio/v/2021.3-unreleased/demo-projects/using-apis-to-pull-dynamic-data)


