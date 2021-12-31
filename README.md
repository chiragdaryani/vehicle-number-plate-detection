# vehicle-number-plate-detection


## Project Description:

* In this project, we develop an Object Detection Model that automatically detects number plates from images of vehicles.  
* We perform the fine-tuning of the SSD-MobileNet V2 Model on our custom image dataset using Tensorflow Object Detection API.
* After we get the bounding boxes for our number plates, we extract the numbers from each region of interest using EasyOCR built on Pytorch. 
* We also apply a filtering algorithm to increase the precision of detections and export the final results into a CSV file
