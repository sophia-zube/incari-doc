# Setting Variable Values and Section End

{% hint style="info" %}
At times where we want to set a value from one of multiple logical outcomes, we can use the SelectData node from the Flow Control category of our Toolbox to consolidate both the Pulse Flow and output data into a single branch of logic. This is incredibly useful for avoiding duplicated logic branches, when multiple outcomes are possible.

This may sound confusing at first and is a slightly complex topic for a beginner tutorial, however, just bear in mind that if you find yourself duplicating a lot of logic, the SelectData node may help drastically reduce duplication.
{% endhint %}

Although we have done our calculation on the change in speed, we need to update our Speed variable to represent the new value. We do this by dragging the value from the result of each of our math nodes and plugging them into our Speed variable.

We _could_ do this by dragging the Speed variable to the graph _twice_ and plugging the [Add and Subtract nodes](../../logic-editor/toolbox/math/basic-math-operation-nodes.md) into each of those nodes, however it is highly recommended \(and good practice\)  to use a SelectData node and just _one_ Speed variable node. That way we are _getting_ our Speed value in one place and _setting_ our speed value in one place.

* Create a SelectData node.
* Drag our Speed variable node to the graph.
* Link the nodes up as shown below.

![](../../.gitbook/assets/11_settingvariablevalue-and-mergingpulsedata.gif)

At this point your logic graph should look like the one below. It is important to practice good housekeeping throughout the development of your applications, as tidy logic graphs, well-named variables and clearly named functions are incredibly important for being able to find what you need as your projects grow in complexity.

![Your node graph should look like the one above.](../../.gitbook/assets/11-partonecomplete.png)

Once you have done this, save the project. This can be done in any of three ways:

1. Click on the "Save" icon at the top left of the application's window.
2. Press File &gt; Save Scene in the application toolbar.
3. Press Ctrl + S.

![](../../.gitbook/assets/save.gif)



