# Brown Gastrotnetology Video Capsule Endoscopy Dataset
The project files in this folder are used to perform technical validation as a part of manuscript submitted to "Scientific Data".

## Files and folders
**Jupyter notebooks**

There are 3 Jupyter notebooks:
1. Step1_Preprocessing.ipynbs  
  This file is designed for setting up required folders and data before begining the training process in the next step.
2. Step2_Training.ipynb  
  This file is designed for training the deep learning model based on training and validation sets.
3. Step3_Testing.ipynb  
  This file is designed for creating a prediction based on the trained model and evaluating the performance on the testing set.

**"csv" folder**

This folder contains csv files that are used in Step1_Preprocessing.ipynbs to extract the image files for training, validation, and testing sets. This is to make sure that the process is reproducible without randomness.


**"InceptionResNetV2" folder**

This folder contains 3 sub-folders (i.e. \model, \modelWeight, and \pic). Mainly, they are used for saving the files generated during the training process. You will also find the pre-trained model in the "\model" subfolder here.

## Authors
Authors: Amber Charoen, Averill Guo, Panisara Fangsaard, Supakorn Taweechainaruemitr, Nuwee Wiwatwattana, Theekapun Charoenpong, and Harlan G Rich

Corresponding author: Amber Charoen (amber.charoen@brown.edu)

## Citation
Pending: Official citation will be created after the manuscript is accepted or published.

## Version
06/09/2022: First version