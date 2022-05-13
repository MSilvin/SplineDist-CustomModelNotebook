[![CC BY 4.0][cc-by-shield]][cc-by]

This work is licensed by Marine SILVIN, (http://ici.igbmc.fr/) under a
[Creative Commons Attribution 4.0 International License][cc-by].

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png
[cc-by-shield]: https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg


## Table of Contents
1. [SplineDist-CustomModelNotebook](#SplineDist-CustomModelNotebook)
2. [Requirements](#Requirements)
3. [How to run the notebook](#How-to-run-the-notebook)
4. [Outputs](#Outputs)
5. [More infos](#More-infos)


# SplineDist-CustomModelNotebook
Creation of a notebook that can apply a custom model trained in SplineDist on a folder full of tiff images.
Following the export of a new model trained in SplineDist [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/HenriquesLab/ZeroCostDL4Mic/blob/master/Colab_notebooks/Beta%20notebooks/SplineDist_2D_ZeroCostDL4Mic.ipynb) from the Zerocostdl4Mic (https://github.com/HenriquesLab/ZeroCostDL4Mic) collection, there was a need to work on a local environment with a specific notebook. Moreover, we wanted to export the labelmap obtain from the model.


### Requirements
* A conda environment (see .yml file or requirement.txt file that contains all the dependencies needed). If it doesn't work, try to install it as the answer of this issue mentionned it : https://github.com/uhlmanngroup/splinedist/issues/2
* Folder with tiff data (1 channel, no stack, no timelapse)


## How to run the notebook
When you have installed the notebook, you can run it by clicking on the "run". You can start only on the import part if you have already done the installations on your environnements (if you use environnements).

## Outputs
This notebook will return tiff files of the labelmap in a Result folder. 

## More infos
N/A
