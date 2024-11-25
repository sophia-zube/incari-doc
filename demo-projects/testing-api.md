# Testing API

## Introduction

This **Testing API** gives the user everything required to understand the tools necessary for creating their own tests in *Python* in order to check their **Incari Projects**. The following four sections provide the details:

* [**Requirements**](testing-api.md#requirements)
* [**Types**](testing-api.md#types)
* [**Template**](testing-api.md#template)
* [**Example**](testing-api.md#example)

## Requirements

It is mandatory to install *Python* to access the **incari Module**, as tests will be written in *Python* outside of **Incari Studio**. 

### Installation Requirements

Python version: 

* 3.10.6, which can be installed [here](https://www.python.org/downloads/release/python-3106/).

### Adding the PATH

A *PATH* is an environment variable which is required for *Python* to function. More on *PATHs* can be found [here](https://en.wikipedia.org/wiki/PATH_(variable)). 

To make the *PATH* permanently available:


* Press `Win + R`, type `sysdm.cpl`, and press `Enter`

* In the *System Properties* window, go to the *Advanced* tab and click *Environment Variables*.

* Under *System Variables*, locate and select `PYTHONPATH`. 
  
  * If it doesn't exist, click `New` and then add:

    * *Variable name*: `PYTHONPATH`

    * *Variable value*: `C:\Program Files\Incari\IncariStudio\2024.1\bin`  

* Click `OK` to save and close all windows.

* Finally, restart the *Command Prompt* or *IDE* for the changes to take effect.

## Types

There are several different *Method Types* handled by the **incari Module**. **Object** *Types* contain certain *Properties* as well. 

The types are:

* [**Object**](testing-api.md#object)
  * [**Properties**](testing-api.md#properties)

* [**Screen**](testing-api.md#screen)

* [**Scene**](testing-api.md#scene)

* [**Mouse**](testing-api.md#mouse)

* [**Keyboard**](testing-api.md#keyboard)

### Object

The **Object** *Methods* are described below. The `property.Name:Strings` are given in the [**Properties**](testing-api.md#properties) section. 

| Method Name | Method Usage | Parameter | Return Type| Method Definition|
| :--- | :--- | :--- | :--- | :--- |
|  `get_id`    | `object.get_id()`     |    --  | `incari.UUID`    |`get_id` returns the [**Debug ID** ](../objects-and-types/attributes/common-attributes/debug-id.md) of an **Object**.| 
| `get_property`     |  `object.get_property("propertyName")`    |   `propertyName:String`   | *value*    | `get_property` returns the value of the chosen [**Property**](testing-api.md#properties) of an **Object**.   |
|  `set_property`    | `object.set_property("propertyName", value)`     |`propertyName:String, value`      | --    |  `set_property` allows the user to set a *value* for a certain [**Property**](testing-api.md#properties).  |

#### Properties

The **Property Names** which correspond to the `property:Name:Strings` given in the section above.

| Property | Property Name| Type | Property Definition| 
| :--- | :--- | :--- | :--- | 
|   Name   |  `_name`    |   **String**   |  The name of the **Object** in **String** format.    |     
| Text     |  `_text`    |   **TranslatableText**   |  The text of a **Text Object**. Only works with **Text Objects**.    |      
|  Size    |  `_currentSize`    |  **Vec2**    |  The `X` and `Y` values of any **Object's** size.    |      
|  Rotation    |  `_currentRotation`    | **Float**     |The current rotation of an **Object** in **Float** format.|      
| Position     |  `_currentPosition`    |   **Vec2**   |   The current position of an **Object** in `X` and `Y` values in *two-dimensional space*.   |     
| Opacity     | `_currentOpacity`     |  **Float**    | The current opacity of an **Object** in **Float** format.     |     
|   Visible   |   `_enabled`   | **Bool**     |   The current visibility of an **Object**. *True* corresponds to visible and *False* corresponds to not visible.   |      
    


### Screen

The *Screen Methods* are described below.

| Method Name | Method Usage | Parameter | Return Type| Method Definition|
| :--- | :--- | :--- | :--- | :--- |
|  `get_id`    |  `screen.get_id()`    |  --    |  `incari.UUID`    |  `get_id` returns the [**Debug ID** ](../objects-and-types/attributes/common-attributes/debug-id.md) of a **Screen**.    |
| `get_keyboard`     | `screen.get_keyboard()`     |  --   |   `incari.Keyboard`   |  `get_keyboard` returns the **Keyboard** associated with the **Screen**.    |
|  `get_mouse`    | `screen.get_mouse()`     |   --   |    `incari.Mouse`  | `get_mouse` returns the **Mouse** associated with the **Screen**.     |



### Scene

The *Scene Methods* are described below.

| Method Name | Method Usage | Parameter | Return Type| Method Definition|
| :--- | :--- | :--- | :--- | :--- |
| `get_id`     |  `scene.get_id()`    |  --    |  `incari.UUID`    |  `get_id` returns the [**Debug ID** ](../objects-and-types/attributes/common-attributes/debug-id.md) of a **Scene**.     |
|  `get_object_by_id`    |  `scene.get_object_by_id()`    |    `incari.UUID`  |  `incari.Object`    |  Returns the **Object** of a specified [**Debug ID**](../objects-and-types/attributes/common-attributes/debug-id.md) for a **Scene**.    |
|  `get_root_object`    |  `scene.get_root_object()`    |  --    |  `incari.Object`    |   Returns the [**Root Object**](../objects-and-types/scene-objects#root-object) of a **Scene**.   |

### Mouse

The *Mouse Methods* are described below.

| Method Name | Method Usage | Parameter | Return Type| Method Definition|
| :--- | :--- | :--- | :--- | :--- |
| `move`     |  `mouse.move(incari.Vec2(x,y))`    |  `incari.Vec2(x1,y1)`    |  --    |   `move` chooses where the **Mouse** should move to.    |
|  `press`    | `mouse.press(incari.Mouse.Button.X)`     | `X` = `incari.Mouse.Button.LEFT` OR `incari.Mouse.Button.RIGHT`     |  --    |  `press` defines if a **Mouse** click is *left* or *right*.    |
| `release`     |  `mouse.release(incari.Mouse.Button.X)`    | `X` = `incari.Mouse.Button.LEFT` OR `incari.Mouse.Button.RIGHT`     |  --    |  `release` defines if a **Mouse** release is *left* or *right*.   |


### Keyboard

The *Keyboard Methods* are described below.

| Method Name | Method Usage | Parameter | Return Type| Method Definition|
| :--- | :--- | :--- | :--- | :--- |
|`press`|`keyboard.press(incari.Keyboard.Key.KEY_NAME)`| `incari.Keyboard.Key.KEY_NAME` (example: KEY_A if `A` is desired key.)| --| `press` defines the key pressed on a **Keyboard**.|
|`release`|`keyboard.release(incari.Keyboard.Key.KEY_NAME`|`incari.Keyboard.Key.KEY_NAME` (example: Key_A if `A` is desired key.) | -- | `release` defines the key released on a **Keyboard**.|



## Template

## Example