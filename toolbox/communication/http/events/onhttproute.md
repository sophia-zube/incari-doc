# On HTTP Route

## Overview

![The On HTTP Route Node.](../../../../.gitbook/assets/onhttproutenode.png)

**On HTTP Route** is an **Event Listener Node** that executes when a `Request` is received  by a specific **Route**, which is set up in the `Attributes`, and returns the data defined by the outputs.

[**Scope**](../../overview.md#scopes): **Project**, **Scene**.

## Attributes

![The On HTTP Route Node Attributes.](../../../../.gitbook/assets/onhttprouteattributes2.png)

| Attribute | Type | Description |
| :--- | :--- | :--- |
| `Configuration` | **Drop-down** | The desired _HTTP_ server, which refers back to the selections made under *HTTP* in the [**Project Settings**](../../../modules/project-settings.md). |
| `Routes` | **Add Elements** | A `Route` is made up of its _HTTP_ `Method` \(either **GET**, **POST**, **DELETE**, **PUT**, or **HEAD**\) and its URL. |

## Outputs

| Output | Type | Description |
| :--- | :--- | :--- |
| `path/name (METHOD)` \(►\) | An **Output Pulse** which executes when a `Request` is received by a specific **Route**.|
| `Headers` | **Dictionary** | _HTTP_ headers in the form of key/value pairs. |
| `Query` | **Dictionary** | Parameters of the call in the form of key/value pairs. |
| `Request ID` | **CustomID** | The unique ID of the request. |

