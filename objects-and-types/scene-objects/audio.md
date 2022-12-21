# Audio

**Audio Objects** provide a means for the user to incorporate aural aspects to a **User Interface**, whether that be music, a chime alert, or a speech file. 

In this version of **Incari Studio** only `.mp3` files are supported. 

To create an **Audio Object**, either click the plus icon in the **Scene Outliner** or right-click in the **Scene Outliner**, hover over `Create`, and locate **Audio**.


![Create Audio Object with Plus Icon.](../../.gitbook/assets/createaudio1.png)

![Create Audio Object with Right-Click and Create.](../../.gitbook/assets/createaudio2.png)

When an **Audio Object** is created, it is initially empty. Also, there is no visual component displayed in the **Scene**, even when a file is selected.

<div>
<figure><img src="../../.gitbook/assets/audioobject1.png" alt=""><figcaption><p>Audio Object before File is Selected.</p></figcaption></figure>
<figure><img src="../../.gitbook/assets/audioobject2.png" alt=""><figcaption><p>Create Audio Object after File is Selected.</p></figcaption></figure>
</div>

The **Audio** can be played, paused, or stopped within its **Scene** of **Incari Studio** by clicking the respective buttons in the **Attribute Editor**.

In order to use **Audios** in a **Project** and have them play in the **Player**, the user needs to use the **Video Nodes** in the **Logic Editor**. More information on using **Video Nodes** can be found [here](../../toolbox/incari/video/README.md) and [here.](../../toolbox/events/video/README.md) For understanding how to use **Object Nodes** in the **Logic Editor**, please refer to this [section](../../objects-and-types/scene-objects/README.md#objects-in-logic) of the *Documentation*.

An example **Logic** configuration can be seen below. This would allow one to play the **Audio** with `A` on their keyboard and stop it with `B`. 

![Example Logic for Using Audio Objects in Incari Player.](../../.gitbook/assets/audioexample.png)
