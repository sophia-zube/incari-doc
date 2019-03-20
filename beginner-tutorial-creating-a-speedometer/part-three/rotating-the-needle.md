# RangeMapper

With our controls, variables and text already set up, all we need to do is add rotation to the needle graphic. Translating the value of a **Variable** into a rotation value is just one of many uses for the [**RangeMapper Node**](../../logic-editor/toolbox/math/advanced-math-nodes.md#rangemapper). It basically takes an **Input** value within one range and outputs its value relative to a second range. For a more detailed description on the behaviour of [**RangeMapper**](../../logic-editor/toolbox/math/advanced-math-nodes.md#rangemapper), and various examples, check out the [**RangeMapper** ](../../logic-editor/toolbox/math/advanced-math-nodes.md#rangemapper)section of the **Advanced Math Nodes** page.

As we can see, when we rotate our needle graphic, the value 0 on our speedometer's face graphic lies at around -135° and the maximum value of 120 lies at 135°. What this means is that we need to take our **Speed Variable**'s value, which we know is always between 0 and 120, and _map_ it to the range of rotation of the needle, which is between -135 and 135.

By adding another instance of our **Speed Variable** to the **Logic Graph**, we can utilise the **Variable Node's OnChange Event**. This allows us to trigger some logic every time there is change in the **Speed** value.

{% hint style="info" %}
* Drag and drop the **Speed Variable** to create another **Variable Node**.
* Add a **RangeMapper Node**.
* Connect the **OnChange Pulse** of **Speed** into the **Input Pulse** of **RangeMapper**.
* Connect the **Output Value** of **Speed** to the **Input** of **RangeMapper**.
* Set the **Input** range to be **an Integer** between 0 and 120.
* set the **Output** range to be an **Integer** between -135 and 135.
{% endhint %}

