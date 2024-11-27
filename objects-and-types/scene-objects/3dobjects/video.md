# Video

A **Video Object** displays a video once a file is selected in the `Video File` **Attribute** or a `Camera input` camera is selected. 0 usually refers to the webcam of a laptop. 

![Video Object Without Any Video.](../../../.gitbook/assets/video20241.png)

As can be seen in the image above, the **Video Object** has an **Attribute** `input type`. Here, `Video file` is selected, but `Camera input` is also possible. 

![Video Object With a Video.](../../../.gitbook/assets/video3d20241.gif)

Once a file is selected, it is displayed in the viewport of the **Scene Outliner**. It can be played, paused, and stopped. Alternatively, the `Camera` would be selected for `Camera input`. This would be 0, 1, 2, and so on, depending on the coding of the devices connected to the user's machine. 

`Preload`is a **Bool**, which when enabled, allows memory to be used on **Project** initializaton and no delay on first play. When disabled, less memory is used and there will be a small delay on first play. 

Additionally, there are several **Nodes** that can be used for incorporating **Video Objects** into the **Logic** of a **Project**. These are the **Media Nodes**. More information can be found [here](../../../toolbox/incari/media/README.md) and [here.](../../../toolbox/events/media/README.md)

