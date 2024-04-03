# Audio 2D

**Audio 2D Objects** provide a means for the user to incorporate aural aspects to a *User Interface*, whether that be music, a chime alert, or a speech file. 

In this version of **Incari Studio** only `.mp3` files are supported. 

To create an **Audio Object**, either click the plus icon in the **Scene Outliner** or right-click in the **Scene Outliner**, hover over `Create`, and locate **Audio**.


![Create Audio Object with Plus Icon.](../../.gitbook/assets/audioimage120232.png)

![Create Audio Object with Right-Click and Create.](../../.gitbook/assets/audioimage220232.png)

When an **Audio Object** is created, it is initially empty. Also, there is no visual component displayed in the **Scene**, even when a file is selected.

While the **Audio Object** has several **Attributes**, the most important  of which is `Audio File` under `Audio`. Here the user can either drag a file from the **Asset Manager** or click the empty file icon and select the desired file from the pop-up Menu. 

<div>
<figure><img src="../../.gitbook/assets/audioimage320232.png" alt=""><figcaption><p>Audio Object before File is Selected.</p></figcaption></figure>
<figure><img src="../../.gitbook/assets/audioimage420232.png" alt=""><figcaption><p>Create Audio Object after File is Selected.</p></figcaption></figure>
</div>

A preview of the **Audio** can be played, paused, or stopped within its **Scene** of **Incari Studio** by clicking the respective buttons in the **Attribute Editor**.

In order to use **Audios** in a **Project** and have them play in the **Player**, the user needs to use the **Media Nodes** in the **Logic Editor**. More information on using **Media Nodes** can be found [here](../../toolbox/incari/media/README.md) and [here.](../../toolbox/events/media/README.md) For understanding how to use **Object Nodes** in the **Logic Editor**, please refer to this [section](../../objects-and-types/scene-objects/README.md#objects-in-logic).

An example **Logic** configuration can be seen below. This would allow one to play the **Audio** with `A` on their keyboard and stop it with `B`. 

![Example Logic for Using Audio Objects in Incari Player.](../../.gitbook/assets/audioexamplewithmedianodes.png)
