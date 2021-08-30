# Overview

![The HTTP Client Node.](../../../.gitbook/assets/httpget.png)

The **HTTP Client Node** has two `Methods` of use. These are **HTTP GET** and **HTTP POST**. 

**HTTP GET** creates a request and returns the response within the *HTTP* protocol. This is very useful when dealing with APIs. A more detailed explanation can be found in the link below. 

**HTTP POST** posts ___.

# Attributes

|Attribute|Type|Description|
|---|---|---|
|`Remote IP`|**User Input**|*HTTP* endpoint (either a URL or IP address).|
|`Remote Port`|**Int**|The port value. For *HTTP*, the standard is 80.|
|`Method`|**Dropdown**|Either **GET** or **POST**, depending on the goal of the user.|
|`Path`|**User Input**|A specific path from the call being referenced in `Remote IP`. Usually, this is the text after the main root URL but before the `?` character.|
|`Authentication`|**Dropdown**|The user selects `Basic` When a username and password are required to access the information, otherwise `None` is chosen.|
|`Default Headers`|**Add Elements**|*HTTP* headers in the form of key/value pairs.|
|`Request Query`|**Add Elements**|Parameters of the call in the form of key/value pairs.|
|`Response`|**Bool**|The user chooses true or false depending on if the response body is binary or not.|

# Inputs

|Input|Type|Description|
|---|---|---|
|*Pulse Input* (►)|**Pulse**|A standard **Input Pulse**, to trigger the execution of the **Node**.|
|`Remote IP`|**String**|*HTTP* endpoint (either a URL or IP address).|
|`Remote Port`|**Int**|The port value. For *HTTP*, the standard is 80.|
|`Path`|**String**|A specific path from the call being referenced in `Remote IP`. Usually, this is the text after the main root URL but before the `?` character.|
|`Headers`|**Dictionary**|*HTTP* headers in the form of key/value pairs.|
|`Query`|**Dictionary**|Parameters of the call in the form of key/value pairs.|



# Outputs

|Output|Type|Description|
|---|---|---|
|*Pulse Output* (►)|**Pulse**|A standard **Output Pulse**, to move onto the next **Node** along the **Logic Branch**, once this **Node** has finished its execution.|
|`OnResponse` (►)|**Pulse**|Flows to additional actions when there is a response.|
|`Status Code`|**Int**|
|`Headers`|**Dictionary**|
|`Body`|**String**|

# See Also

# External Links

