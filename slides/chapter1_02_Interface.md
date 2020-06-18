---
type: slides
---

# The RStudio Interface

---

# The RStudio Interface

<img src="RStudioPanels.jpg" width="75%">

Notes: The first time you open RStudio, you will see a window which has three panels as shown. Each of these panels has different purpose and these will be described throughout this section.
---

# Section 1: The Console

<img src="Console.jpg" width="75%">

Notes: This is where commands and text output will appear when they are run. Commands can be typed directly into the console after the prompt symbol `>`. To run a command, hit Enter after typing it. Commands can also be run from a script (This is recommended).

If your console is showing a `+` on the left hand side then this is likely due to a parenthesis that has not been closed - if you are not sure where to close the parenthesis you can press Esc to return to the prompt symbol.

---

# Section 2: The Environment

<img src="Environment.jpg" width="75%">

Notes: The environment panel has multiple tabs, but we'll focus on the Environment tab and the history tab.

*Environment*

Each time you create a new object in R it will appear in the environment. This is where you will find a list of all variables or object that are available to call by name. This is very useful for checking the types of objects that have already been created and find out what their names are.

*History*

The history is similar to the environment, but it stores r commands which have been run during a session. You can search through these for a previously run command using the search bar at the top right of the panel.

---

# Section 3: Files

<img src="Files.jpg" width="75%">

Notes: This panel has multiple tabs. We will focus on the Files, Plots, Packages and Help tabs. The Viewer tab is used for more advanced features

*Files*

This tab acts as a file browser. You can navigate your way through the files on your computer. You can also use this to set your **working directory** (more on that later!)

*Plots*

When you run a command to create a plot it will show up under the Plots tab. If you have created several plots, then there are arrows which will allow you to cycle through your plots. You can then export the current plot for use in reports.

*Packages*

R packages contain sets of functions, which usually link together to perform some specific analysis. You can see which packages you have installed and load packages from this tab.

You are likely to need to use a package that is not available as part of the default installation of R. To use this type of package you will first have to install it. There are two ways to do this:

run the command `install.packages("package_name")`
or using the mouse navigate to **Tools > Install Packages…** and type the name of the package into the dialogue box

There are a lot of packages that are installed with R, but to reduce the time it takes to open R, the packages that are loaded by default is limited. To load a package run the command `library(package_name)`. Note that the package name does not need to be in quotation marks.

*Help*

This is where any help files/R Documentation will appear. To obtain the help file for a particular R function type `?function` into the console, where function can be replaced with the name of any R function that you require help with.

---

# Time to summarise