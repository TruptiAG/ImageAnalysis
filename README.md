# ImageAnalysis


## Image Processing Methods to Automatically Track Intensity Changes In Submicron-sized Cellular Structures

We present an image analysis workflow starting with image segmentation and particle analysis. The workflow we propose is likely to be useful for tracking and measuring changes in submicron structures in microscopy.


Description for the notebook files and folders:

 |Name                        | Type         |Description
 |----------------------------|------------- |------------ 
 | functions.ipynb            | Notebook     |This file contains the functions that are used in this pipeline
 | Analysis-Method1.ipynb     | Notebook     |Measures PP1 intensity in CDKi and DMSO Cells,generates graphs and csv files for particles measurements 
 | Analysis-Method2.ipynb     | Notebook     |Measures Astrin intensity in WildType and Q1012,generates graphs and csv files for particles measurement 
 | graphs                     | folder       |generated graphs
 | Experiment Name            | folder       | This folder contains following subfolders
 | mask                       | folder       |tif images of masks
 | pp1 /channel               | folder       |tif images of the channel 
 | labelled _images           | folder       |generated and labelled images

 
 
    Folder Structure for experiments
    .
    ├── Experiment Name
     ├── mask                  # mask images
     ├── pp1                    # channel images
     ├── labelled_images        # labelled and overlay images
     ├── csvs                   # particle analysis csv files
  
  
 




