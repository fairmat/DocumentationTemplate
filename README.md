Documentation Template
=====================

Templates used to build the LaTeX documentation of plugins.

In order to be able to build the documentation of the various plugins this project is needed to be cloned at the same level of the other plugin projects, just like the DVPLReferences project.

After cloning them the folder structure should be similar to this

Containing Folder:

* DocumentationTemplate (this repository)
* DatesGenerator (A plugin project)
* DVPLReferences (The references required to build plugins)

After this project has been cloned it's possible to go in the folder containing the documentation, for example ./DatesGenerator/Documentation/ and use LaTeX as usual (eg: pdflatex DatesGenerator.tex). If everything was setup correctly the related pdf file will be generated in the Documentation folder.

Note that all documentation is under Creative Commons by NC SA.
