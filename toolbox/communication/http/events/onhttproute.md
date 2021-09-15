# On HTTP Route

## Overview

![The On HTTP Route Node.](https://github.com/cgi-studio-gmbh/incari-doc/tree/8b797c630dccaa2b415ca3ed261027f0467693f1/.gitbook/assets/onhttproute.png)

**On HTTP Route** is an **Event Listener Node** that executes when a `Route` is received and returns the data defined by the outputs.

## Attributes

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Dropdown** | The desired _HTTP_ server. |
| `Routes` | **Add Elements** | A `Route` is made up of its _HTTP_ `Method` \(either GET or POST\) and its URL. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| _Pulse Output_ \(►\) | **Pulse** | A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution. |
| `Headers` | **Dictionary** | _HTTP_ headers in the form of key/value pairs. |
| `Query` | **Dictionary** | Parameters of the call in the form of key/value pairs. |
| `Request ID` | **CustomID** | The unique ID of the request. |

