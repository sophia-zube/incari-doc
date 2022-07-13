# Exporter

The **Exporter** **Module** allows the user to export a **Project** to a chosen export folder. In addition to exporting the **Project**, **Exporter** creates a copy of **Incari Player** in the same folder. This makes it possible to save and open a **Project** in **Player** format at another time. 

![](../.gitbook/assets/exporter-module.png)

After exporting a **Project**, the target folder will have:

* A folder with a copy of **Incari Player**.
* A folder with the exported **Project**.
* A `run.bat` file.

The **Project** can then be started by launching `run.bat`.

It is also possible to export a **Project** from the command line with the command `IncariCLI.exe /p="<project-path>" /export /output="<export-folder-path>"`.

