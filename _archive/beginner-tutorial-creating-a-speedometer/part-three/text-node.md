# Text Node

We now have the placeholder text in our **Text Object**, and a **Function** to format the speed, but the two aren't yet linked. The way that we change the _content_ of **Text Objects** is by using the **Text Node**.

The **Text Node** is created like any other **Node**, however, without a **Text Object** assigned to its **Text Object Attribute**, it won't know _which_ text it needs to change. We can assign this by selecting the **Node** and dragging a **Text Object** onto the **Attribute**'s thumbnail.

{% hint style="info" %}
* Create a **Text Node** and assign the **SpeedText** to its **Text Object Attribute**.
{% endhint %}

![](../../.gitbook/assets/assigningtextobject.gif)

Because **Text** takes a single **String Input**, we can simply modify the existing **Console** logic that we created earlier.

{% hint style="info" %}
* Delete the **Console Node** from our existing logic.
* Drag our **Text Node** in its place.
* Update the **Connections**.
{% endhint %}

![](../../.gitbook/assets/swappingconsoleforfunction.gif)

