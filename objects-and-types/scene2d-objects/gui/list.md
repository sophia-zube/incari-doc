# List

A **List** is a **GUI 2D Object** that allows the user to create a *list*. The contents of the list, and any visual components, can be customized in the **Attributes**.  


![List and List Item Attributes.](../../../.gitbook/assets/listattributes2.png)

![](../../.gitbook/assets/listattributes3.png)

The `List`, `List Item`, `Text`, and `List Item Icon` categories cover visual aspects of the **List Object** and any distancing and spacing specifications of its components.

The `JSON File` contains the actual data of the **List** and is a required **Attribute** that must be provided by the user. For example, a *JSON* file could contain something like this:


```
    {
        "icon": "",
        "text": "you collected"
    },
    {
        "icon": "",
        "text": "over 9000"
    },
    {
        "icon": "",
        "text": "overhours"
    }
```
This results in a **List** that appears like this (with some other visual **Attributes** changed):

![](../../../.gitbook/assets/2dlistexample.png)