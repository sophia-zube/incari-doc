# Best Standards and Practices 

It is understandable that learning any new software can be a bit overwhelming. However, we at **Incari** aim to streamline the learning process and limit how daunting it can be. Therefore, this page highlights some **Incari** standards and practices that the user can incoporate into their creative process in order to make using **Incari Studio** that much more enjoyable. 

## Conceptualizing

**Incari Studio** is a powerful tool which offers a multitude of ways for executing the same general concepts <!-- better word here--> -- this enables the user to apply it to an abundance of different situations. Yet, this also means that planning the structure of a **Project** is incredibly important. There are some questions which should be considered at the beginning of every **Incari Project** before commencing with the details.

### 1. Planning the General Structure

<details open>

<summary>

  Is performance/consumption a very important factor for this __Project__? 

</summary> 


If yes, the **Project** should be split into as many **Scenes** as rationally makes sense. This way the user can utilize the **Scene** loading feature <!-- need link here-->in **Incari** to load **Scenes** and **Assets** only when they are needed.

This significantly decreases any burden on the target device and increases performance.

</details>

<details open>
<summary>

Does this **Project** use *3D* components or rely on *3D* animations? 

</summary>
 
If not, the user might consider using [**Scene2Ds**](../../objects-and-types/project-objects/scene2d.md). They are less powerful when it comes to things such as masking or animating, but it is much easier to turn them into pixel-perfect implementations. This is especially true when implementing a design from *Figma*, *Adobe XD*, or other similar softwares. **Incari Studio** can import these and render them comparably within a **Scene2D**. 

Furthermore, if *3D* components end up being needed further on, the user can always add a **Scene2D** as an [**Overlay**](../../objects-and-types/scene-objects/overlay.md) to a **Scene**.

</details>

<details open>

<summary>

Does the **Project** require a lot of similar components used in a number of different places? 

</summary>

If the answer is yes, build [**Prefabs**](../../objects-and-types/prefabs/README.md) for these components. They make the **Logic** significantly easier to understand and maintain.

Best part is, if this component gets updated in the design at some point, the user just needs to update the main **Prefab**. Same for the **Logic** driving it.

</details>

<details open>

<summary>

Does this **Project** contain multiple **Screens**?

</summary>

If the answer is yes, one should consider if all of them are run on a single device or if each **Screen** is run on a seperate target device. 

In the case that the whole **Project** runs on a single device, it is possible to create a single **Incari Project** for all of the **Screens**. 

In the case that the **Project** runs on multiple targets, each **Screen** needs to have its own **Incari Project**. If needed, additional communication needs to be implemented between the **Projects**.

</details>

### 2. Planning the Logic 

<details open>

<summary>

Is this **Project** data driven?



</summary>

If the answer is yes -- and in most cases it should be -- avoid hard-coded values as much as possible. The extensive and structured use of **Variables** (see [**Logic**](#logic) section below) is crucial to the maintainability of the **Project** further on.

</details>

<details open>

<summary>

Do the interactions in this **Project** rely on the screen/device on which the **Project** is being run?

</summary>

If yes, the user should consider setting a *static variable* in the beginning for the screen resolution (or aspect ratio, depending on the situation) and use it for all **Logic** purposes. In the future, **Incari** will have a **Get Screen Resolution Node**.

For instance, assume there is an interaction where an **Object** is being moved from `W/4` to `3W/4` on the *X* axis, with *W* representing the screen width. If one were to hard code the positions, any screen size change (even if the aspect ratio stays the same) will result in the interaction being broken. A suggested resolution path could be as follows:

* Create a variable called `static_global_vec2_screenResolution` to store the screen resolution.

* Create an **Array** to store the initial and end location of the **Object** (e.g. `scene1_arr-vec2_obj1Locations`).

* On **Project** initialization, use a function to calculate `.75` of the resolution width and set the items in the **Array** accordingly.

* Next, when building the animation, fetch the correct value from the **Array**.

Although the initial setup is slightly heftier, in a **Project** with a multitude of these interactions where the resolution changes, all that will be needed is to change a single variable instead of modifying dozens of different **Nodes**.

</details>


## Logic