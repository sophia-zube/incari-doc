# Plugins

The **Plugins Module** allows you to activate or deactivate different components within **Incari**. This provides you with the foundation for a scalable structure, combining creativity and functionality to ensure **Incari** supports your individual needs. At the moment, this is specific to **Serial Communication**.

The **Plugins Module** looks like this when it is opened: 

![](../.gitbook/assets/pluginsstart.png)

After clicking the arrow, **Communication** options are revealed. The checkmark is an important visualization of how the **Plugins** function. When a component is activated, a checkmark is present next to the name. If deactivated, the checkmark disappears. This makes it easy to see which components are in use or not without needing to click each one. 

![](../.gitbook/assets/pluginsserialmanager.png)

## SerialManager 

After clicking on **SerialManager**, its options will show. All **Serial Communication** related components are encompassed by the **SerialManager**. 

To refresh, **Serial Communication** is a form of data transmission where data is sent bit by bit. More information can be found [here](https://en.wikipedia.org/wiki/Serial_communication). Within **Incari**, this is done by using the [**Serial Nodes**](../toolbox/communication/serial/README.md) and connections are configured in the [**Project Settings**](project-settings.md#serial). They add the necessary functionality to a **Project** that requires this type of communication. However, you may decide that you would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, you need simply to locate the toggle labeled `Activated` and click it once.  

![](../.gitbook/assets/pluginsserialmanager2_green.png)

**Incari** will alert you of this by outputting this message to the screen:

![](../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **IncariStudio**) you will deactivate the **SerialManager**. 

Once you have followed these steps, the checkmarks by **Plugins Editor**, **SerialManager** will be gone and the toggle is now labeled `Deactivated`. 

![](../.gitbook/assets/deactivated1_green.png)

To activate again, you just need to repeat this by clicking `Deactivated` and saving and restarting again. 

