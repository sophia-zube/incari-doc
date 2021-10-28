# What's New

Many new features have been added to the release of **Incari Studio** 2021.4. Here is a list of the features you need to know.

* **Integration with Third-Party Software**
  
    **Incari** now lets users incorporate several third-party software into their **Projects** that encompass different categories. These include math libraries ([*Eigen*](https://eigen.tuxfamily.org/index.php?title=Main_Page) and [*GLM*](https://github.com/g-truc/glm)), an **MQTT** message broker ([*Mosquitto*](http://mosquitto.org/)), **HTTP** clients ([*cpp-httplib*](https://github.com/yhirose/cpp-httplib) and [*civetweb*](http://civetweb.github.io/civetweb/)), an **HTTP** server ([*civetweb*](http://civetweb.github.io/civetweb/)), *websocket* ([*civetweb*](http://civetweb.github.io/civetweb/)), and a *Javascript* library for web applications ([*SocketIO*](https://socket.io/)). These integrations improve the capabilities of **Incari Projects** and provide further functionality with a little boost from other software. 

* **Performance Improvements**
  
    A few simple performance improvements have been added to the newest version of **Incari**. The user can now export a **Project** as a single `.zip` file, binarize a **Project** to export, as well as take advantage of the enhanced rendering engine performance. These will help strengthen the **Incari** experience. 

* **Compiler in Command Line Interface \(version 2\)**

    In the previous version, the **Logic** of a **Project** could be compiled directly from the command line. This allowed to then directly run a **Project** in **Incari Player** without having to open the **Project** in **Incari Studio**. This remains the same, except now it is also possible to generate code on save. 

    To reiterate, the command to compile the **Logic** of a **Project** is: `IncariCLI.exe /p="<project-path>"`.

* **Serial Communication**
  
    *Serial* *Communication* is a type of communication that sends single bits of data at a time, sequentially, through a communication channel/bus. This method of communication is now included in **Incari**, the settings of which can be found in the **Project Settings** after clicking the **Project** Menu at the top. More information can be found [here](https://docs.incari.com/2021.4/modules/project-settings#serial). Additionally, there are new [**Serial Communication Nodes**.](still need link)  

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

    
  
* **Websprite Nodes**

    New **Nodes** allowing to handle [**Web Sprite** **Objects**](scene-objects/web-sprite.md):

    * [**Get Remote URL**](../toolbox/incari/websprite/get-remote-url.md)
    * [**Set Remote URL**](../toolbox/incari/websprite/set-remote-url.md)
    * [**Web Sprite Reload**](../toolbox/incari/websprite/web-sprite-reload.md)
    * [**On WebSprite Load**](../toolbox/events/websprite/on-websprite-load.md)


