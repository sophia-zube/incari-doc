# HTTP

## Introduction

The **HTTP Nodes** provide a means for the user to perform several actions within the _HTTP_ protocol. _HTTP_, or _Hypertext Transfer Protocol_, allows for communication between servers and clients by way of requests and responses using different methods. To use the **HTTP Nodes** in **Incari**, the user needs to locate the [**HTTP Attributes**](../../../modules/project-settings.md#can) in **Project Settings** and add a server. Both *HTTP* and *HTTPS* are supported. 

## HTTP Guideline

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* These **Nodes** cover important functions of **HTTP Communication**.
  * **On HTTP Route** executes when an **HTTP Route** is received.
  * **On HTTP Server Start** executes once a connection to an **HTTP Server** is completely established.
  * **On HTTP Server Stop** executes once a connection to an **HTTP Server** is completely disconnected from. 
  * **HTTP Client** implements the *post* and *get* functions of the **HTTP** protocol. 
  * **HTTP Response** defines a response for a particular request.
  * **HTTP Server Start** starts the connection with an **HTTP Server**. 
  * **HTTP Server Stop** stops the connection with an **HTTP Server**.
* To properly stop a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.

## Contents

* [**Events**](events/)
  * [**On HTTP Route**](events/onhttproute.md)
  * [**On HTTP Server Start**](events/onhttpserverstart.md)
  * [**On HTTP Server Stop**](events/onhttpserverstop.md)
* [**HTTP Client**](httpclient.md)
* [**HTTP Response**](httpresponse.md)
* [**HTTP Server Start**](httpserverstart.md)
* [**HTTP Server Stop**](httpserverstop.md)


## External Links

* More information on [_HTTP_](https://en.wikipedia.org/wiki/Hypertext_Transfer_Protocol) on Wikipedia.
* More information on [*HTTPS*](https://en.wikipedia.org/wiki/HTTPS) on Wikipedia. 

