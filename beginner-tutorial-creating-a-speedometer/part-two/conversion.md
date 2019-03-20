# Conversion

Now that you understand a bit about **Data Types**, let's look at how we can take mismatched **Input**/**Output Types**, and make them compatible with one another. To do this we have an all-purpose **Conversion Node**. Once added, all we need to do is set the **Node's Attributes** to match our desired **Input**/**Output Types**, and make the necessary connections.

Because we want to see the **Speed** value every time it is changed, we will utilise its **OnChange Event**.

{% hint style="info" %}
* Add a **Conversion Node** between **Speed** and **Console**.
* Set the **Input Data Type** to **Int**.
* Set the **Output Data Type** to **String**.
* Connect **Speed**'s **OnChange Event** to **Conversion**'s **Input Pulse Socket**.
* Connect **Speed**'s **Value Output** to **Conversion**'s **Input Socket**.
* Connect **Conversion**'s **Output Pulse** to **Console**'s **Input Pulse**.
* Connect **Conversion'**s **Output** to **Console**'s **Message Input**.
{% endhint %}

![](../../.gitbook/assets/speedtoconsole.gif)

