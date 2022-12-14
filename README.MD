# SACM ACEditor

An OMG standard compliant model-based tool that supports the specification of Assurance Cases for Safety-Critical Systems. This tool comprises a graphical editor that supports the specification of assurance case in compliance with OMG Structured Assurance Case Metamodel (SACM) [version 2.2](https://www.omg.org/spec/SACM/2.2/About-SACM/). 
## Eclipse update site
The Eclipse update site for the latest version of the SACM ACEditor including the GSN constraints extensions and MBAC Instantiation can be found [here](https://master.d52pu3gfwomel.amplifyapp.com/site.xml). For the instalation due to dependencies issues we recomend the [Eclipse Epsilon](https://www.eclipse.org/epsilon/).

## Examples 
The models with some examples can be download from [here](https://master.d52pu3gfwomel.amplifyapp.com/files/workspace.zip).

## Tutorial and Usage
After installing the plugins in your Eclipse IDE open the workspace and import the projects.

You can run the instantiation program by right-clicking in the file with ".sacm2", opening the popup menu, and selecting "ACEditor MBAC > Instantiate SACM 2.2 Model". The instantiation runs on EMF model files. After instantiation you can right click in the output file and select "Initialize sacm2_diagram diagram file". This will create a model compatible with eclipse GMF. 

In the diagram view, it is possible to navigate inside a package by "double click". For all elements a popup menu "ACEditor" is available after right-clicking on a model element whit the option "Show Element View". This opens a powerful dialog for viewing and editing model elements' properties.