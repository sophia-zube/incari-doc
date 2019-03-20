# Color Attributes

**Color Attributes** are used to set the colour and opacity of several **Objects** in **INCARI**. They can be set in a variety of ways:

* Using the _saturation_/_brightness_ picker.
* Using the _hue_ and _alpha_ sliders.
* Setting a 8-digit **ARGB** _hex code_.
* Manually setting _hue_, _saturation brightness_ \(**HSB**\) levels.
* Manually setting _red_, _green_, _blue_ and _alpha_ \(**RGBA**\)

   levels.

![](../../.gitbook/assets/colorattribute.png)

### Hex Codes

Currently the hex code **Field** of the **Color Attribute** only accepts _full_ 8-digit hex codes. It does _not_ support shorthand hex codes \(e.g. \#FFF\), and does not automatically interpret 6-digit hex codes as 8-digit hex codes.

Additionally, the first two digits of the code represent the _alpha_ value, not the _red_ value, therefore 6-digit hex codes must have an alpha value added to _the front_ of the code \(e.g. \#FF0000 would become \#FFFF0000\).

### Hue, Saturation and Brightness

**HSB** values in **INCARI** are within the range 0 - 1, which may differ from other software. Hue properties, for example, are often given in degrees \(0° - 360°\), while saturation and brightness are often represented as a percentage \(0% - 100%\). To translate values from another application to **INCARI**, you may need to convert the values first.

### Red, Green, Blue and Alpha

**RGBA** are all within the range of 0 - 255. This is a fairly common convention, however there are some cases where alpha values are given as a percentage, or within the range 0 - 1. As with **HSB**, values may need to be converted beforehand.



