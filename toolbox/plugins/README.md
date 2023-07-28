# Plugins

## Introduction

The **Plugins** **Nodes** appear once the **Logic Plugin** is activated. This process will be described in detail. They allow users to customize their **Logic**. 

# Example 

This **Node** appears after a particular process. The user requires access to the *Windows PowerShell* and the folder in which their **Incari Studio** appears, along with all its files. The user will also need to install [*CMake*](https://cmake.org/) and make sure it is added to PATH upon installation. 

After clicking on the **Incari Studio** folder, its files should look something like this: 

![Incari Studio Folder Example.](../../.gitbook/assets/logicplugin1.png)

Locate the `PluginExample` folder. Copy that to the `Documents` folder on your device.

![Locating and Copying the PluginExample Folder.](../../.gitbook/assets/logicplugins2.gif)


Once that is done, open the *Windows PowerShell* and choose the file path pointing to the `PluginExample\build` in `Documents` as directory. This can be done by using the command `cd file\path`.

Next, the user must use the following command:

` cmake .. -G "Visual Studio 17 2022" -A x64 -DINCARI_DIR="file\path"` 

Here, copy everything exactly and replace `file\path` with the file path to where **Incari Studio** is actually installed. This will likely be in the `Program Files` folder on your *Windows* device. 

The resulting output of the above command is as follows:

![Output of First CMake Command.](../../.gitbook/assets/logicplugin3.png)

The second crucial command to run is:

`cmake --build . --config Release`

When this command has finished running, the user can check back in the `PluginExample` folder that everything executed properly.

![Checking for output Folder.](../../.gitbook/assets/logicplugin4.png)

The contents of the `output` folder (`plugins`) needs to be copied into the installation folder of the user's **Incari Studio**. 

![Copying the output Folder to the plugins Folder.](../../.gitbook/assets/logicplugins6real.gif)

Now it's time to open **Incari Studio**. When it's up and running, the user can check that the **Plugins** and the **Logic Editor** have the new data created during the previous process. 

![Logic in Plugins.](../../.gitbook/assets/logicpluginresultplugins.png)

![New Node in Logic Editor.](../../.gitbook/assets/logicpluginresultnode.png)

## Contents

* [**(JSON) Scale Vector**](jsonscalevector.md)