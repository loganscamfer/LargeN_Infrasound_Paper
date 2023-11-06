Code for Scamfer & Anderson (2023)
Exploring background noise with a large-N infrasound array: waterfalls, thunderstorms, and earthquakes
Geophysical Research Letters

CONTENTS
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

The Folder 'pickle_files/' contains multiple data files seperated into subfolders (e.g. N_3, N_9, N_full, etc.) These are beamformed results of array_processing() in ObsPy. array_processing parameters can be found in the 'Methods' section and Supporting Information.



