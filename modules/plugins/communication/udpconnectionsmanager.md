# UDP

After clicking on **UDP** in the **Plugins Module**, its options will show. All **UDP Communication** related components are encompassed by the **UDP Plugin**. 

To refresh, **UDP**, or *User Datagram Protocol*, is a connectionless form of data communication that is a part of the Internet protocol suite. More information can be found [here](https://en.wikipedia.org/wiki/User_Datagram_Protocol). Within **Incari**, this is done by using the [**UDP Nodes**](../../../toolbox/communication/udp/README.md) and connections are configured in the [**Project Settings**](../../project-settings/udp-connection.md). They add the necessary functionality to a **Project** that requires this type of communication. However, the user may decide that they would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, the user needs simply to locate the toggle labeled `Activated` and click it once.  

![](../../../.gitbook/assets/udppluginsbefore20241.png)

**Incari** will alert the user of this by outputting this message to the screen:

![](../../../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **Incari Studio**) the user will deactivate the **UDP Plugin**. 

Once the user has followed these steps, they will see that after restarting **Incari Studio** and going to the **Plugins Editor**, the checkmark by **UDP** will be gone and the toggle labeled `Deactivated`. 

![](../../../.gitbook/assets/udppluginsafter20241.png)

To activate again, the user just needs to repeat this by clicking `Deactivated` and saving and restarting again. 