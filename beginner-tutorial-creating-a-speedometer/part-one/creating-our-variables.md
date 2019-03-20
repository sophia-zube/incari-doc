# Creating Our Variables

As with programming, we often need to create a container to hold some information or data, which can be accessed at various different places within our logic, whether it is _getting_ or _setting_ the value of the data. This is where variables come in.

To create a variable in INCARI's logic editor

1. Go into the Variables tab.
2. Give the variable a name e.g. "Speed".
3. Select the variable's [type](../../logic-editor/data-types/) from the Data Type dropdown.
4. Click Add to create the variable.
5. You can then set the variables default value from the "Initial Value" attribute of the variable.

For our Speedometer we are going to have two [integer-type](../../logic-editor/data-types/int.md) variables: one representing the current speed of the vehicle, and the other representing the amount to increase/decrease the speed by when we press one of the arrow keys.

* Create a variable for our vehicle's current speed and call it "Speed", with a default value of 0.
* Create a variable for our speed increment and call it "Increment", with a default value of 5.

![Creating a variable.](../../.gitbook/assets/8_creatingvariables.gif)

