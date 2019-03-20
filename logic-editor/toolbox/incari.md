# Incari

## Object

Used to _get_ and _set_ the visual and transformational properties of an Object and to trigger events based on user-interaction with that object.

### Usage

An Object node can be created by dragging and dropping an object from the Scene Outliner into the Logic Editor graph.

The referenced object can be edited by dragging a new object from the Scene Outliner onto the Object thumbnail in the Node attribute editor.

`Position`, `Rotation`, `Scale`, `Alpha` and `isVisible` are all available as both inputs and outputs. There are also three additional Pulse outputs, relating to user-interaction; `OnClick`, `OnDoubleClick` and `OnChange`.

![When the object is clicked, it grows in size. We use the Object node to get the value of a property, trigger an event and set the value of a property.](../../.gitbook/assets/objectexamplesimple.png)

![The result of the above logic.](../../.gitbook/assets/objectdemo.gif)

## Project

The Project node is used to trigger an event once the project is loaded and is useful for initialising the values of objects or trigger things such as introduction animations.

### Usage

![The above example sets a Text Object to be visible as soon as the project is loaded.](../../.gitbook/assets/projectexample.png)

## Screen

The Screen node is used to link the individual scenes of a project to one another.

### Usage

Switching between multiple scenes of a Screen is made possible using the Screen node. A common use case would be to use the `OnClick` event of a graphic or other object, to take the user to a different scene within the application.

The node also has an `OnSceneSet` event, which triggers whenever the current Scene is set.

![By utilising the OnClick method of an object, it is possible to switch between different scenes.](../../.gitbook/assets/screenusage.png)

![The result of the above logic.](../../.gitbook/assets/sceneswitch.gif)

## Text

The Text node is used to dynamically set the text content of a Text object and takes a String value as an input.

### Usage

Like many other nodes in Incari, you can simply drag and drop the node from the Toolbox, or right click and select the node in the Logic Editor graph. To link the node to your Text object, you then need to drag and drop your Text object from the Scene Outliner into the Text Object attribute of the node.

It is a highly useful node, used for displaying speed information, battery levels, directions and much more.

### Advanced Usage

As the text object is based on html, it is possible to add `<span>` tags to give text [custom inline styling](https://www.w3schools.com/tags/tag_span.asp).

