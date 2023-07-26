# Plugins

## Introduction

The **Plugins** **Nodes** appear once the **Logic Plugin** is activated. This process will be described in detail. They allow users to customize their **Logic**. 

# Example 

This **Node** appears after a particular process. The user requires access to the *Windows PowerShell* and the folder in which their **Incari Studio** appears, along with all its files. The user will also need to install [*CMake*](https://cmake.org/) and make sure it is added to PATH upon installation. 

After clicking on the **Incari Studio** folder, its files should look something like this: 

![Incari Studio Folder Example.]()

Locate the `PluginExample` folder. Copy that to the `Documents` folder on your device.

![Locating and Copying the PluginExample Folder.]()


Once that is done, open the *Windows PowerShell* and choose the file path pointing to the `PluginExample\build` in `Documents` as directory. This can be done by using the command `cd file\path`.

Next, the user must use the following command:

` cmake .. -G "Visual Studio 17 2022" -A x64 -DINCARI_DIR="file\path"` 

Here, copy everything exactly and replace `file\path` with the file path to where **Incari Studio** is actually installed. This will likely be in the `Program Files` folder on your *Windows* device. 

The resulting output of the above command is as follows:

![Output of First CMake Command.]()

The second crucial command to run is:

`cmake --build . --config Release`

When this command has finished running, the user can check back in the `PluginExample` folder that everything executed properly.

![Checking for output Folder.]()

This `output` folder needs to be copied into the `plugins` folder of the user's **Incari Studio**. 

![Copying the output Folder to the plugins Folder.]()

## Contents

* [**(JSON) Scale Vector**](jsonscalevector.md)