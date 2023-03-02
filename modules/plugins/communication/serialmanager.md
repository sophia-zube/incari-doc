# Serial

After clicking on **Serial**, its options will show. All **Serial Communication** related components are encompassed by the **Serial Plugin**. 

To refresh, **Serial Communication** is a form of data transmission where data is sent bit by bit. More information can be found [here](https://en.wikipedia.org/wiki/Serial_communication). Within **Incari**, this is done by using the [**Serial Nodes**](../../../toolbox/communication/serial/README.md) and connections are configured in the [**Project Settings**](project-settings.md#serial). They add the necessary functionality to a **Project** that requires this type of communication. However, the user may decide that they would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, the user needs simply to locate the toggle labeled `Activated` and click it once.  

![](../../../.gitbook/assets/serialpluginnewactivated.png)

**Incari** will alert the user of this by outputting this message to the screen:

![](../../../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **IncariStudio**) the user will deactivate the **Serial Plugin**. 

Once the user has followed these steps, they will see that after restarting **Incari Studio** and going to the **Plugins Editor**, the checkmark by **Serial** will be gone and the toggle labeled `Deactivated`. 

![](../../../.gitbook/assets/serialpluginnewdeactivated.png)

To activate again, the user just needs to repeat this by clicking `Deactivated` and saving and restarting again. 