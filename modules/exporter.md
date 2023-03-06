# Exporter

The **Exporter** **Module** allows the user to export a **Project** to a chosen location. In addition to exporting the **Project**, **Exporter** can create a copy of **Incari Player** in the same folder. This makes it possible to save and run a **Project** without the need of **Incari Studio**.

There are two tabs in the **Exporter** **Module**: [**Settings**](#settings) and [**Deploy**](#deploy).

Furthermore, find below an easy guide on [**Exporting a Project**](#exporting-a-project) with the **Exporter** **Module**, divided between the two possible cases of *Target Platforms*:

* [**Host Target**](#host-target)
* [**Different Target**](#different-target)

## Settings

![](../.gitbook/assets/exporter-settings.png)

### General

* `Target`: *Operating System* in whose **Incari Player** version the exported version of the **Project** will be played.

### Options

* `Only Project`: Whether only the **Project** will be exported or the **Project** alongside a copy of **Incari Player**.

## Deploy

![](../.gitbook/assets/exporter-deploy.png)

* `Export Folder`: The location in the local machine to which the **Project** will be exported.


<!-- ![](../.gitbook/assets/exporter-module.png) -->

## Exporting a Project

There are two slightly different procedures for exporting a **Project** depending on the `Target` chosen:

* [**Host Target**](#host-target)
* [**Different Target**](#different-target)

### Host Target

Exporting a **Project** for the *Host* `Target` is very straightforward as this `Target` is already available and selected by default. To export the **Project**, simply click on the `Export` button on the top menu.

![](../.gitbook/assets/exporter-export.png)

A pop-up message indicating that the export was successful will appear.

![](../.gitbook/assets/exporter-success.png)


After exporting a **Project**, the export folder will have:

* A folder with the exported **Project**.
* A `run.bat` file.
* A folder with a copy of **Incari Player** (only if `Only Project` was set to *false*).

The **Project** can then be started by launching `run.bat`.

It is also possible to export a **Project** from the command line. There are two cases, which are equivalent to whether the `Only Project` option is set to *true* or *false* in [**Settings**](#settings), when exporting from **Incari Studio**.

For exporting the **Project** alongside a copy of **Incari Player**, run the command:

* `IncariCLI.exe /p="<project-path>" /export /output="<export-folder-path>"`.

For exporting just the **Project**, without a copy of **Incari Player**, run the command:

* `IncariCLI.exe /p="<project-path>" /export /output="<export-folder-path>" /no-player`.



<!-- with the command `IncariCLI.exe /p="<project-path>" /export /output="<export-folder-path>"`. 

Add `/no-player` to the command to export just the **Project** without a copy of **Incari Player**, this is equivalent to setting `Only Project` to *true* in the [**Settings tab**](#settings) when exporting from **Incari Studio**. Omitting `/no-player` from the command will result in exporting the **Project** alongside a copy of **Incari Player**, just as setting `Only Project` to *false* when exporting from **Incari Studio**. -->


### Different Target

Exporting a **Project** for a different *Target* than the *Host* requires a few preparatory steps that will be explained in detail:

**Setting up WSL**

*WSL* stands for *Windows Subsystem for Linux* and is a tool that allows users to run a *Linux* environment directly on *Windows*. It is needed for building the **Project** for the desired *Target Platform*. 

Find more information about *WSL* on the links provided in the **External Links** section below.

To set up *WSL*, follow these steps:

1. Either on *Windows PowerShell* or *Command Prompt*, run the following *command*: `wsl --install`. This will install *WSL* and the latest *Ubuntu* version.
2. Restart *Windows*.
3. Go to the *Microsoft Store* and install *Ubuntu 20.04* or run on the *PowerShell* or *Command Prompt* the following command: `wsl --install -d Ubuntu-20.04`.
4. Enter your credentials in the pop-up window that appears. If it does not appear, run the command `wsl` on the *PowerShell* or *Command Prompt* and enter your credentials.
5. Set-up *Ubuntu 20.04* as the default *distribution* by running the command `wsl --set-default` on the *PowerShell* or *Command Prompt*.

**Preparing Incari Studio**

For exporting to a different *Target Platform* than the *Host*, a *cross-compiled* version of **Incari Player** for the desired *Target* is necessary.

1. Acquire **Incari Player** for the desired `Target` *platform*. For this, an **Enterprise Account** is needed.
2. Copy the *cross-compiled* version of **Incari Player** in the following location: `%AppData%\IncariStudio\CrossCompile\<target-triple>\Incari\IncariPlayer\<IncariStudio/Player-version>/`. 

The `<target-triple>` in the *path* where the *cross-compiled* version of **Incari Player** should be located is dependent on the desired *Target Platform*.

These are a few examples for `<target-triple>` to be used in the *path*:
* `x86_64-linux-gnu`, for *Linux x86-64*.
* `aarch64-linux-gnu`, for *Linux arm64*.
* `arm-linux-gnueabihf`, for *Linux arm32*.

**Exporting the Project**

After following all the previous steps, everything is ready for exporting a **Project** to the desired *Target* *Platform*. For this:

1. Open the **Project** to be exported in **Incari Studio** and go to the **Exporter Module**.
2. Add the desired `Target` by using the plus icon on the top left.

![Adding a Target.](../.gitbook/assets/exporter-addtarget2.png)

![Exporter with *Linux x86-64* Target added.](../.gitbook/assets/exporter-wlinux.png)

3. Choose the desired `Export Folder` on the [**Deploy**](#deploy) tab. 
4. Click on the `Export` button on the top menu.

![](../.gitbook/assets/exporter-exportlinux.png)

A pop-up message indicating that the export was successful will appear.

![](../.gitbook/assets/exporter-success.png)


After exporting a **Project**, the export folder will have:

* A folder with the exported **Project**.
* A `run.sh` file.
* A folder with a copy of **Incari Player** for the desired `Target` (only if `Only Project` was set to *false*).

The **Project** can then be started in the *Target Platform* by launching `run.sh`.

## External Links

* [*WSL Documentation*](https://learn.microsoft.com/en-gb/windows/wsl/).