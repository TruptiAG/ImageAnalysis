# ImageAnalysis


## Image Processing Methods to Automatically Track Intensity Changes In Submicron-sized Cellular Structures

We present an image analysis workflow starting with image segmentation and particle analysis. The workflow we propose is likely to be useful for tracking and measuring changes in submicron structures in microscopy.


Description for the notebook files and folders:

 |Name                        | Type         |Description
 |----------------------------|------------- |------------ 
 | functions.ipynb            | Notebook     |This file contains the functions that are used in this pipeline
 | Analysis-Method1.ipynb     | Notebook     | Generating csv files for the particles measurement for the images in the folder 
 | Plots.ipynb                | Notebook     | Reads the csv files and generate plots
 | graphs                     | folder       |generated graphs
 | Experiment Name            | folder       | This folder contains following subfolders
 | mask                       | folder       |tif images of masks
 | pp1                        | folder       |tif images of the channel 
 | labelled _images           | folder       |generated and labelled images

 
 
Folder Structure
.
+-- Experiment Name
|   +-- mask
|   +-- pp1
|   +-- labelled_images
|   +-- csvs
+-- _graphs
