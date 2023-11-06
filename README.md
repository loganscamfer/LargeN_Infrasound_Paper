# Code for Scamfer & Anderson (2023): Exploring background noise with a large-N infrasound array: waterfalls, thunderstorms, and earthquakes
## Geophysical Research Letters

### Contents
This repository contains Python code and data to reproduce parts of Fig. 2-4 in the paper, and Supporting Information Fig. S1-3,5.

Folder 'code/':
The Folder 'code/' contains Python code to fully reproduce Fig. 2, and can reproduce Fig. 3-4 without the maps.
Individual panels (3) of Fig. 5 can be reproduced should you obtain WWLLN data and place it in the 'imported_data/' folder. 
World Wide Lightning Location Network data is available at nominal cost from http://wwlln.net. 
When requesting WWLLN data, search the box (50N,126W) - (36N,102.5W) for the following days:
April: 29, 30th 2020
May: 19, 20, 30th 2020
June: 5, 6th 2020
The subfolder 'code/supporting_information/' also contains code to reproduce the Supporting Information Fig. S1-3, and S5.

The Folder 'Figures/' contains image files of the figures in the paper.
The subfolder 'code/maps/' contains QGIS map files and .jpg files with the maps for Fig. 3-4.

The Folder 'imported_data/' contains data files including Snake River discharge data and Stanely Ranger station temperature data. Should you obtain WWLLN data this is where you should place the files.

The Folder 'pickle_files/' contains multiple data files seperated into subfolders (e.g. N_3, N_9, N_full, etc.) These are beamformed results of array_processing() in ObsPy. Array_processing parameters can be found in the 'Methods' section and Supporting Information. We have included the products of array_processing() because creating them using raw data is computationally expensive and can take very long periods of time.

The File XP.PARK is an XML
### Before running code:
For the code to run successfully, you must have Python and dependent packages installed. An easy way to do this uses Anaconda or Miniconda (which you must install beforehand):
```
conda deactivate
conda create -y -n large_N_infrasound python=3.9.12 matplotlib=3.6.2 obspy=1.4.0 pandas=1.5.2 numpy=1.21.6
conda activate large_N_infrasound
```
These commands should run on any python terminal or IDE. When running code, you must set the 'Large_N_Infrasound_Paper/' as your working directory.


