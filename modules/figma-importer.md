# Figma Importer 

The **Figma Importer** allows the user to import their projects (or parts of their projects) from *Figma* and render them in **Incari Studio** with comparable retention of designs. As of 2023.2, there are some exceptions to this which will be desribed in greater detail [below](figma-importer.md#exceptions).

## Access

![Figma Importer Before Importing.](../.gitbook/assets/figmaimporterbeforeaccess.png)

Before any options for importing can become available, the user must locate the necessary information to access the *Figma* project. These are the `Authentication Token` and the `Document Key`.

The `Authentication Token` can be generated in a *Figma* user's account settings, the process of which is described [here](https://www.figma.com/developers/api#authentication). 


The `Document Key` is located in the *url* of the project, after `file` such as in:

`https://www.figma.com/file/jCFQWXBJWk6LtqsI4wLi4j/project_example_name`

Here, the `Document Key` is `jCFQWXBJWk6LtqsI4wLi4j`

Inputting these two into their respective text boxes will result in the user gaining access. 

![Successful Import.](../.gitbook/assets/figmasuccessfulimport1.png)

In the event that this attempt is unsuccessful, a warning will be given. 

![Figma API Warning.](../.gitbook/assets/figmaerror1.png)

## Import 

There are initially two **Attributes**, `Document Name` and `Figma Pages`.  

### All Pages

![Figma Pages --> All Pages.](../.gitbook/assets/figmaallpages.png)

Selecting `All Pages` will import each *Figma Page* into a new and separate Scene2D. For example, if a *Figma* project has two *Pages* called `Page 1` and `Page 2`, this wil result in two new **Scene2Ds** in `Unassigned Scenes` in the **Project Outliner** labeled `Page 1` and `Page 2`. 

### Single Page

![Figma Pages --> Single Page.](../.gitbook/assets/figmasinglepage.png)

Selecting `Single Page` will make the `Figma Page Selection` and `Figma Scene Selection` **Attributes** visible. 

`Figma Page Selection` gives a dropdown of all the possible *Figma Pages* available in the accessed *Figma* project. 

![Figma Page Selection.](../.gitbook/assets/figmapageselection.png)

`Figma Scene Selection` gives a dropdown of all the possible **Scene2Ds** to import into as well as the options `Active Scene` (the **Scene2D** that is currently open) and `Create Scene` (creates a new **Scene2D** on import).



## Exceptions