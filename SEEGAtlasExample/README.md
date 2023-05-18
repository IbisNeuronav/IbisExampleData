# Description

This directory contains two example data for the SEEG plugin for IBIS.

# How to load data

1. Download or clone the repository on your local computer
	1.1. ```git clone https://github.com/IbisNeuronav/IbisExampleData.git```
2. Download binary files "_IbisSEEGAtlas1.0.x.zip_" of IBIS with the SEEG plugin here: https://github.com/IbisNeuronav/IbisPluginsExtraSEEG/releases/tag/v1.0 
3. Unzip the files in a local directory and run "_IbisSEEGAtlas1.0.x\ibis.exe_"
4. (optional) Copy the configuration files:
	4.1. Download config files here: https://github.com/IbisNeuronav/IbisPluginsExtraSEEG/releases/download/v1.0/SEEGAtlasData.zip 
	4.2. Unzip the files into "_C:\Users\\<your_username>\\.Ibis\SEEGAtlasData_"
	-- <your_username> refers to your windows username
	-- if the directory ".Ibis" doesn't exist, create an empty directory with this name or run Ibis once (it will be automatically created)
5. Once Ibis is running with the SEEGAtlas plugin, clic on "Load MRI/CT From Dir" on the top of the right pannel, and select the directory of the example you want to load. Different options are possible:
	5.1. If "Segmentations (pre-space)" is selected: pre-implentation image with the associated atlas labelmap will be loaded
	5.2. If "Template" is selected:
	5.3. If "Electrodes (pos-space)" is selected: post-implentation data are loaded
6. To load electrodes, use "Load All Electrodes" button and select "_\SEEGAtlasExample\\\<Example>\electrodes\_" directory