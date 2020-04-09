# Building the Output String

### Conversion

Now that we have logic to manage the format of our speed, we need to combine it with the value from our **Speed Variable**. Because **Speed** is an **Integer**, we first need to convert it to a **String**.

{% hint style="info" %}
* Add a **Conversion Node** and set the **Input** and **Output Data Types** to be **Int** and **String** respectively.
* Plug our **Function**'s **Speed Input** into the the **Input Socket** of the **Conversion Node**.
* Plug the **Pulse** of our **SelectData Node** into the **Pulse Socket** of the **Conversion Node**.
{% endhint %}

![](../../.gitbook/assets/conversion.gif)

### Concatenation

The last step before outputting our **String** is to combine the speed _value_ and speed _unit_. The process of adding one **String** to the end of another is known as _concatenation_, and INCARI has a **Node** for this task, called **Concat Strings**.

If we use the **Concat Strings Node** with our existing **Strings**, we will run into a problem. Rather than outputting "120 km/h",  for example, we will actually get "120km/h". Because **Strings** are sequences of characters and a **Space** is technically a character, we need to adjust our **String Value Nodes** to have a leading whitespace character.

{% hint style="info" %}
* Change the value of top **String Node** from "km/h" to " km/h".
* Change the value of bottom **String Node** from "mph" to " mph".
{% endhint %}

We then need to setup a **Concat Strings Node**.

{% hint style="info" %}
* Add a **Concat Strings Node**.
* Set the **Output Pulse** of the **Conversion Node** to the **Input Pulse Socket** of our **Concat Strings Node**.
* Connect the **Output** of our **Conversion Node** to the _first_ **Input** of the **Concat Strings Node**.
* Connect the **Output** of our **SelectData Node** to the _second_ **Input** of the **Concat Strings Node**.
{% endhint %}

The final thing that we need to complete our first **Function** is make the necessary **Output Connections**.

{% hint style="info" %}
* Add the **Output Pulse** of our **Concat Strings Node** into the **Function**'s **Pulse Output**.
* Add the **Output String** of our **Concat Strings Node** into the **Function**'s **SpeedString Output**.
{% endhint %}

![](../../.gitbook/assets/concatenation%20%281%29.gif)



