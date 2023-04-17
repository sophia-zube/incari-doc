# Custom Shading Model

This model represents a material that provides the visual qualities to a car's paint features. It allows for selecting and editing: 

* `Vertex Shader`
* and `Fragment Mapping`

All these **Attributes** are described in greater detail below. 

![](../../.gitbook/assets/customshadingmodel.gif)

## Attributes

### Material

![Material](../../.gitbook/assets/customshadingmodel2.png)

This **Attribute** provides the `Name` of the **Material** as well as the `Shading model` type. It also sets the `Alpha` value if it is toggled on. 

The `Alpha` channel is additional to the RGB channels and adds a kind of transparency to the object by mixing the background and foreground colors. For example, if the `Alpha` value is set to 0.5, then this would result in a 50% mix of the object and its background, providing a semi-translucent quality. 

### Shaders

![](../../.gitbook/assets/customshadingmodel3.png)

The `Vertex Shader` allows the user to provide a file which

Similarly, the `Fragment Shader` enables the user to give a file which