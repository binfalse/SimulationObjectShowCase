# SimulationObjectShowCase

This is going to be a fully featured **Simulation Object** (a [Research Object](http://www.researchobject.org/) containing a simulation study) that will help demonstrating the concepts and best practices.

## What's in here

This Simulation Object represents the study described by Calzone *et. al.* in [*Dynamical modeling of syncytial mitotic cycles in Drosophila embryos*](http://dx.doi.org/10.1038%2Fmsb4100171), Mol Syst Biol. 2007; 3: 131.
I decided for that study because

* the corresponding article is published as open access ([Creative Commons Attribution‐NonCommercial‐NoDerivs](http://creativecommons.org/licenses/by-nc-nd/3.0/)),
* the study is already available in [SBML](http://sbml.org/) format ([BIOMD0000000144](http://www.ebi.ac.uk/biomodels-main/BIOMD0000000144)),
* the study is already available in [CellML](http://www.cellml.org/) format ([exposure](http://models.cellml.org/exposure/1a3f36d015121d5596565fe7d9afb332)),
* I've been working with that model before.

## The Structure

The files of the simulation study are organised in folders:

* **documentation:** Files describing the model and its behaviour, such as the article published in 2007.
* **model:** Files that describe and encode the biological system, such as the model in SBML/CellML format and figures.
* **experiment:** Files which encode the actual experimental setup, such as SED-ML simulation descriptions.
* **result:** Files that were obtained by running the *in silico* experiment, such as graphs and tables.

Please note, that this structure is not mandatory.

## Explore the CombineArchive

So far, this Simulation Object can only be explored by browsing through the files, e.g., on GitHub.
However, you might want to explore the contents of the equivalent CombineArchive. You can open it in the [CombineArchive WebInterface](http://webcat.sems.uni-rostock.de/) by simply importing it using the following link:

[http://webcat.sems.uni-rostock.de/rest/import?name=AllSingingAllDancing&remote=http://scripts.sems.uni-rostock.de/getshowcase.php](http://webcat.sems.uni-rostock.de/rest/import?name=AllSingingAllDancing&remote=http://scripts.sems.uni-rostock.de/getshowcase.php)
