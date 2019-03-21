# Lights \*

**INCARI** has two types of **Light Object**; the **Spot Light** and the **Point Light**.

The **Point** **Light** is _omnidirectional_, meaning that light is emitted equally in all directions; while the **Spot Light** is _directional_ and will only light the area that it is rotated towards. Additionally, unlike **Point Light**, **Spot Light** supports shadow mapping, and has a extra set of **Attributes** for that purpose.

| Attribute | Spot Light | Point Light |
| :--- | :--- | :--- |
| `Color` | ✔ | ✔ |
| `Brightness` | ✔ | ✔ |
| `Attenuation` | ✔ | ✔ |
| `Radial Falloff` | ✔ | ✘ |

## Light

### Color

`Color` determines the colour of the light being emitted.

Please not that the `Color` **Attribute**'s _brightness_ level will affect the brightness of the light itself. It is therefore recommended that you always have the brightness level set to 1, and use the actual `Brightness` **Attribute** to alter the intensity of the light.

`Color`'s _alpha_ level has no effect.

### Brightness

`Brightness` governs the intensity of the light, with lower values giving less intense light emission and vice versa.

![](../../../.gitbook/assets/brightness.gif)

### Attenuation

`Attenuation` relates to the spread, or reach, of the light. Lower levels only illuminate close **Objects**, whereas high levels allow the light to reach **Objects** that are further away.

![](../../../.gitbook/assets/attenuation.gif)

### Radial Falloff

`Radial Falloff` is used to change the smoothness of the light falloff. Lower levels will give a smoother transition between light and dark areas, but will be darker overall. Higher levels give a much more contrasting light-to-dark transition and will appear comparatively brighter.

This **Attribute** is only available on the **Spot Light Object**.

![](../../../.gitbook/assets/radialfalloff.gif)

## Shadow Mapping

### Enable

### Resolution

### Kernel Size

### Clip Near

### Offset

