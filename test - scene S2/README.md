## Instructions

All the scripts are ready to segment the test images of scene S2, in the dataset of this repository. You only have to run the scripts in Python.
If you want to apply the method to other images, you have to change the path in the variable "file" and the coordinates of the region of interest in the variable "colors".

The results will be saved in the /results folder.

The code of our method includes the scripts to perform the segmentation in images processed with the three pipelines explained in the paper: 
- Folder Gamma_1 contains images processed with the sensor approach
- Folder Gamma_22 contains images processed with the sensor-display approach
- Folder Perceptual contains images processed with the Perceptual approach.
