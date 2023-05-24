# MAVLink

After clicking on **MAVLink** in the **Plugins Module**, its options will show. All **MAVLink Communication** related components are encompassed by the **MAVLink Plugin**. 

To refresh, **MAVLink Communication**, or *Micro Air Vehicle Link*, is used for communication with small vehicles, like drones. More information can be found [here](https://mavlink.io/en/). Within **Incari**, this is done by using the [**MAVLink Nodes**](../../../toolbox/communication/mavlink/README.md) and connections are configured in the [**Project Settings**](../../../modules/project-settings/mavlink.md). They add the necessary functionality to a **Project** that requires this type of communication. However, the user may decide that they would rather deactivate this portion of **Incari** to heighten performance and stability. 

To do this, the user needs simply to locate the toggle labeled `Activated` and click it once.  

![](../../../.gitbook/assets/mavlinkbefore.png)

**Incari** will alert the user of this by outputting this message to the screen:

![](../../../.gitbook/assets/pluginsserialmanageroffmessage.png)

By following these instructions (save and restart **IncariStudio**) the user will deactivate the **MAVLink Plugin**. 

Once the user has followed these steps, they will see that after restarting **Incari Studio** and going to the **Plugins Editor**, the checkmark by **MAVLink** will be gone and the toggle labeled `Deactivated`. 

![](../../../.gitbook/assets/mavlinkafter.png)

To activate again, the user just needs to repeat this by clicking `Deactivated` and saving and restarting again. 
