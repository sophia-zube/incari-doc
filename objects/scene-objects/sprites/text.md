# Text

## Text

### Value

`Value` defines the text that will appear in the **Text Object**. This can be any sequence of characters that the font supports, including special characters such as emojis 😉.

{% hint style="info" %}
Additionally, the `Value` **Attribute** can be used to add extra styling in the form of HTML/CSS. This is achieved using `<span>` tags and is only recommended to users who are familiar with these languages.
{% endhint %}

```markup
Without CSS
<br>
<span style="
    font-style: italic;font-weight:bold;
    background:linear-gradient(#FEE140 0%, #FA709A 100%);
    -webkit-background-clip:text;-webkit-text-fill-color:transparent;">

    With CSS
</span>
```

![](../../../.gitbook/assets/css.png)

### Font Family

`Font Family` allows you to select a generic font family \(`monospace`, `serif`, `sans-serif`\) or add a custom font.

To add a custom font, simply drag it into the **Asset Manager** from your OS' file explorer. To use that font, drag it from the **Asset Manager** onto the `Font Family` **Attribute** of a **Text Object** in the **Attribute Editor**.

### Alignment

Alignment works like any other word processor. You can align your text to be left-aligned, center-aligned or right-aligned, using the `left`, `center` and `right` options respectively.

![](../../../.gitbook/assets/alignment.png)

### Transform 
The `Transform` attribute can *capitalize*, set to a *lower* or *upper* case, text appearing in the **Text Object**.

### Font Size

`Font Size` defines the approximate height, in pixels, from the _lowest descent_ to the _highest ascent_ of a font.

![](../../../.gitbook/assets/font-size.png)

### Letter spacing (px)
The approximate amount of spacing in pixels between each letter of the text.

### Font Color / Background Color

**Colors** can be set in various ways in Incari and work very much like they do in other software. You can manually adjust the the **HSB** / **RGBA** values or input a **Hex Code**, using their corresponding [**Color Attribute**](../attributes/attribute-types/color-attributes.md).

### Style File (CSS)

![](../../../.gitbook/assets/objects/scene-objects/sprites/text/CSSstyle.PNG)

The `Style File` **Attribute** is used to apply *CSS text styling* to a **Text Object**. The **Attribute** accepts a *CSS text style* assert that can be created in the **Asset Manager** and edited in the **Code Editor**.

To assign a *CSS text style* **Asset** to the **Attribute**, drag and drop it onto the **Asset** slot of the **Attribute**.

### Size (unit)
*Size* of the displayed text.

## Sprite

Additionally, **Text** also shares **Common Attributes** of the **Sprite** category; which are:

* `Alpha`
* `Flip U` and `Flip V`
* `Sort Index`

## Advanced

### Link resolution to size
The value of the `Resolution` **Attribute** would be updated to be equal to that of the `size` **Attribute** if the *toggle* is activated.

### Resolution (px)
The *resolution* of the displayed text.

## Additional Information

### Size and Resolution

Although you may already be familiar with the `Size` and `Resolution` **Attributes** of the **Camera Object**, things work slightly differently with **Text** and **Web Sprite Objects**.

With **Camera**, `Resolution` relates to the resolution of a _physical_ piece of hardware ,i.e., a display. With **Text** and **Web Sprite**, however, both `Size` and `Resolution` relate to something which exists in _virtual_ 3D space. So although, like **Camera**, the `Size` **Attribute** defines the **Object**'s size in 3D space, the `Resolution` **Attribute** defines the resolution of the content that will be stretched to fit that space.
