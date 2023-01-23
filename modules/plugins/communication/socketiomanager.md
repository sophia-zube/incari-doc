# SocketIOManager

After clicking on **SocketIOManager**, its options will show. All **Serial Communication** related components are encompassed by the **SerialManager**. 

To refresh, **SocketIO Communication** is a popular form of bidirectional data communication often used for web applications. More information can be found [here](https://socket.io/docs/v4/). Within **Incari**, this is done by using the [**SocketIO Nodes**]() and connections are configured in the [**Project Settings**](../../project-settings.md). They add the necessary functionality to a **Project** that requires this type of communication. However, the user may decide that they would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, the user needs simply to locate the toggle labeled `Activated` and click it once.  

![](../../../.gitbook/assets/pluginssocketio.png)

**Incari** will alert the user of this by outputting this message to the screen:

![](../../../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **IncariStudio**) the user will deactivate the **SocketIOManager**. 

Once the user has followed these steps, they will see that after restarting **Incari Studio** and going to the **Plugins Editor**, the checkmark by **SocketIOManager** will be gone and the toggle labeled `Deactivated`. 

![](../../../.gitbook/assets/socketiomanager2.png)

To activate again, the user just needs to repeat this by clicking `Deactivated` and saving and restarting again. 