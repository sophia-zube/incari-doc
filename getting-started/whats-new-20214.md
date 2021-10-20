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
    xxx