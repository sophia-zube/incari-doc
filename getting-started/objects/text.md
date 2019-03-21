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

![](../../.gitbook/assets/css.png)

### Size and Resolution

Although you may already be familiar with the `Size` and `Resolution` **Attributes** of the **Camera Object**, things work slightly differently with **Text** and **Web Sprite Objects**.

With **Camera**, `Resolution` relates to the the resolution of a _physical_ piece of hardware ,i.e., a display. With **Text** and **Web Sprite**, however, both `Size` and `Resolution` relate to something which exists in _virtual_ 3D space. So although, like **Camera**, the `Size` **Attribute** defines the **Object**'s size in 3D space, the `Resolution` **Attribute** defines the resolution of the content that will be stretched to fit that space.

### Font Family

`Font Family` allows you to select a generic font family \(`monospace`, `serif`, `sans-serif`\) or add your own custom font.

To add a custom font, simply drag it into the **Asset Manager** from your OS' file explorer. To use that font, drag it from the **Asset Manager** onto the `Font File` **Attribute** of a **Text Object** in the **Attribute Editor**.

### Alignment

Alignment works like any other word processor. You can align your text to be left-aligned, centre-aligned or right-aligned, using the `left`, `center`and `right`options respectively.

![](../../.gitbook/assets/alignment.png)

### Font Size

`Font Size` defines the approximate height, in pixels, from the _lowest descent_ to the _highest ascent_ of a font.

![](../../.gitbook/assets/font-size.png)

### Font Color / Background Color

**Colors** can be set in various ways in INCARI and work very much like they do in other software. You can manually adjust the the **HSB** / **RGBA** values or input a **Hex Code**, using their corresponding [**Color Attribute**](../attributes/attribute-types/color-attributes.md).

## Sprite

### Alpha

`Alpha` determines the opacity of a **Sprite** with 0 being completely transparent and 1 being completely opaque.

### Flip U / Flip V

The horizontal and vertical coordinates in most 2D graphics programs are referred to as _XY_ coordinates. In 3D applications, though, it is conventional to call these _UV_ coordinates to differentiate between 3D _mesh_ transformation coordinates and 2D _texture_ transformation coordinates.

The `Flip U` and `Flip V` **Attributes** simply inverts the direction of the corresponding axis, meaning that`Flip U` flips a **Sprite** _horizontally_, while `Flip V` will flip it _vertically_.

### Sort Index

Because **INCARI** works in 3D, it has no way of automatically discerning which elements should be shown on top of which, when they occupy the same area in 3D space. It is therefore necessary to manually define the _sort order_ of **Sprites** to ensure that they are layered correctly.

This is done by manipulating the `Sort Index` **Sprites** with higher values being rendered above lower values. If **Sprites** have the same `Sort Index` **Value**, then there is no guarantee that they will be shown correctly, and it is therefore recommend that you assign a unique **Value** to each **Sprite** unless you are certain that they will never overlap one another.

