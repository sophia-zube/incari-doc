
# WebSocket

After clicking on **WebSocket** in the **Plugins Module**, its options will show. All **WebSocket Communication** related components are encompassed by the **WebSocket Plugin**. 

To refresh, **WebSocket Communication** is a form of data transmission that is bidirectional and sends data from a client to a server or vice versa via the same connection channel. More information can be found [here](https://en.wikipedia.org/wiki/WebSocket). Within **Incari**, this is done by using the [**WebSocket Nodes**](../../../toolbox/communication/websocket/README.md) and connections are configured in the [**Project Settings**](../../project-settings/serial.md). They add the necessary functionality to a **Project** that requires this type of communication. However, the user may decide that they would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, the user needs simply to locate the toggle labeled `Activated` and click it once.  

![](../../../.gitbook/assets/pluginswebsocket20232before.png)

**Incari** will alert the user of this by outputting this message to the screen:

![](../../../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **Incari Studio**) the user will deactivate the **WebSocket Plugin**. 

Once the user has followed these steps, they will see that after restarting **Incari Studio** and going to the **Plugins Editor**, the checkmark by **WebSocket** will be gone and the toggle labeled `Deactivated`. 

![](../../../.gitbook/assets/pluginswebsocket20232after.png)

To activate again, the user just needs to repeat this by clicking `Deactivated` and saving and restarting again. 
