# Default Shadeless Model 

This model represents a material which displays a solid color and offers no response to light placement. It is rather simple, only allowing for selecting and editing:
 
* `Diffuse Color`, `Texture`, and `Blending`. 

All these **Attributes** are described in greater detail below.


![](../../.gitbook/assets/shadelessmodel1.png)


## Attributes

### Material
![Material](../../.gitbook/assets/shadelessmodel2.png)

This **Attribute** provides the `Name` of the **Material** as well as the `Shading model` type. It also sets the `Alpha` value if it is toggled on. 

The `Alpha` channel is additional to the RGB channels and adds a kind of transparency to the object by mixing the background and foreground colors. For example, if the `Alpha` value is set to 0.5, then this would result in a 50% mix of the object and its background, providing a somewhat see-through quality. 


### Diffuse
![Diffuse](../../.gitbook/assets/shadelessmodel3.png)

`Color` of `Diffuse` sets the base diffuse color of the model. 

`Texture` takes any image to add any desired visual information. 

Using `Blending`, the `Texture` and `Color` are combined. If `Blending` is set to 1 then 100% of the `Texture` is displayed on the **Object**. If 0.5, then it displays a 50/50 ratio of `Texture` and `Color`. 