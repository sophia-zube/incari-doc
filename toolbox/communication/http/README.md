# HTTP

## Introduction

The **HTTP Nodes** provide a means for the user to perform several actions within the _HTTP_ protocol. _HTTP_, or _Hypertext Transfer Protocol_, allows for communication between servers and clients by way of requests and responses using different methods. 

The **HTTP Nodes** allow the user to set up a server or connect to an already existing server. To set up a server on the local machine in **Incari**, the user needs to locate the [**HTTP Attributes**](../../../modules/project-settings.md#can) in **Project Settings** and add a server. To connect to an external server, the **HTTP Client Node** should be used. Both *HTTP* and *HTTPS* are supported. 

## HTTP Guideline

With the **HTTP Communication Nodes**, except the **HTTP Client Node**, the user can create a server on the local machine. From there, they can process requests and send respective responses as desired. With the **HTTP Client Node**, the user can make any request to any server.

The following guideline shows the steps needed for setting up a server on a local machine. 

* To properly start a connection, see the [**General Guideline**](../README.md#general-guideline) on the Communications Introduction page.
* Once the connection has been established, there are a couple of **Nodes** that cover important functions of **HTTP Communication**.
  * [**On HTTP Route**](events/onhttproute.md) executes when an **HTTP Request** from a specified **Route** is received. 
  * [**HTTP Response**](httpresponse.md) defines a response for a particular request.
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

