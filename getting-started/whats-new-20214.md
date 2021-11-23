# What's New

Many new features have been added to the release of **Incari Studio** 2021.4. Here is a list of the features you need to know.

* **New Incari Hub**
  
    The updated **Incari Hub** now serves as a central access point to all **Incari** products. It allows to install the latest versions of **Incari** software and obtain [**Demo Projects**](../demo-projects/overview.md) to get started with **Incari**. 

* **Performance Improvements**
  
    A few simple performance improvements have been added to the newest version of **Incari**. The user can now binarize a **Project** to export, as well as take advantage of the enhanced rendering engine performance. These will help strengthen the **Incari** experience. 

* **Serial Communication**
  
    Communication via serial interfaces has been introduced for this new version. **Incari** can now receive and process all data that is received serial bus. This allows to directly use GPS mice, IR controllers, proximity sensors, temperature sensors, etc.
    
    In **Incari**, the **Serial Communication Settings** can be found in the **Project Settings** after clicking the **Project** Menu at the top. More information can be found [here](https://docs.incari.com/2021.4/modules/project-settings#serial). 
    
    Additionally, there are new **Serial Communication Nodes**:

    * [**On Serial Error**](../toolbox/communication/serial/events/onserialerror.md)
    * [**On Serial Packet Receive**](../toolbox/communication/serial/events/onserialpacketreceive.md) 
    * [**On Serial Start**](../toolbox/communication/serial/events/onserialstart.md)
    * [**On Serial Stop**](../toolbox/communication/serial/events/onserialstop.md)
    * [**Serial Send Packet**](../toolbox/communication/serial/serialsendpacket.md)
    * [**Serial Start**](../toolbox/communication/serial/serialstart.md)
    * [**Serial Stop**](../toolbox/communication/serial/serialstop.md)

* **String Manipulation Nodes**

    Several new **Nodes** allowing to manipulate **Strings** have been introduced with this release:

    * [**Compare**](../toolbox/string/compare.md)
    * [**Contains**](../toolbox/string/contains.md)
    * [**Length**](../toolbox/string/length.md)
    * [**Lower**](../toolbox/string/lower.md)
    * [**Replace**](../toolbox/string/replace.md)
    * [**ReplaceRegex**](../toolbox/string/replaceregex.md)
    * [**Split**](../toolbox/string/split.md)
    * [**Upper**](../toolbox/string/upper.md)

    
  
* **WebSprite Nodes**

    New **Nodes** allowing to handle [**Web Sprite** **Objects**](scene-objects/web-sprite.md):

    * [**Get Remote URL**](../toolbox/incari/websprite/get-remote-url.md)
    * [**Set Remote URL**](../toolbox/incari/websprite/set-remote-url.md)
    * [**Web Sprite Reload**](../toolbox/incari/websprite/web-sprite-reload.md)
    * [**On WebSprite Load**](../toolbox/events/websprite/on-websprite-load.md)

* **On-Screen Keyboard Nodes**
    
    These new **Nodes** allow the user to add functionality to an **On-Screen Keyboard**.

    * [**On On-Screen Keyboard Key Pressed**](../toolbox/events/on-screenkeyboard/ononscreenkeyboardpressed.md)
    * [**On-Screen Keyboard Clear Input**](../toolbox/incari/on-screenkeyboard/onscreenkeyboardclearinput.md)
    * [**On-Screen Keyboard Get Input**](../toolbox/incari/on-screenkeyboard/onscreenkeyboardgetinput.md)
    * [**On-Screen Keyboard Move Selection**](../toolbox/incari/on-screenkeyboard/onscreenkeyboardmoveselection.md)
    *  [**On-Screen Keyboard Press Button**](../toolbox/incari/on-screenkeyboard/onscreenkeyboardpressbutton.md)