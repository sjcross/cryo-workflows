# Cryo alignment workflows
Workflows to handle images of EM grids imaged both by cyro EM and fluorescence microscopy.  These workflows are constructed using the [ModularImageAnalysis (MIA)](htps://github.com/mianalysis/mia) plugin for Fiji.

This repository contains the following workflows:

- "WF1_Colocalisation.mia" 
- "WF2_Grid_focussing.mia"
- "WF3_Rendering.mia"

## Installation
To use these workflows, please follow the steps below.  The same installation is compatible with all three worfklows:

1. Go to the Fiji (version 20260307-1417) download page [here](https://downloads.imagej.net/fiji/archive/stable/20260307-1417/) and get the zip file corresponding to your system.
2. Extract the zip file to a location with read/write access (e.g. your documents folder)
3. Download the "MorphoLibJ_-1.6.2.jar" file from [here](https://github.com/ijpb/MorphoLibJ/releases/download/MorphoLibJ_-1.6.2/MorphoLibJ_-1.6.2.jar) and move this to the "plugins" folder of your new Fiji.
4. Download the "MIA_-1.7.26.jar" file from [here](https://github.com/mianalysis/mia/releases/download/v1.7.26/MIA_-1.7.26.jar) and move this to the "plugins" folder of your new Fiji.
5. Download the "mia-dependencies-v1.7.26.zip" file from [here](https://github.com/mianalysis/mia/releases/download/v1.7.26/mia-dependencies-v1.7.26.zip) and extract it.  Take the final folder (i.e. the one with several .jar files inside) and copy this to the "jars" folder of your new Fiji.
6. Download the latest version of this repository by clicking here, then extract this zip file to somewhere with read/write access.

Note: While it is possible to install MIA directly from the ImageJ Updater (see [here](https://mianalysis.github.io/guides/getting-started/) for details), the method listed above is recommended to ensure compatibility with these workflows.

## Usage