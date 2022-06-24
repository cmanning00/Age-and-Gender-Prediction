# Age and Gender Prediction (Work in progress!!!)

In this project I will be designing and training convolutional neural networks to predict the age and gender of an individual given a photo of their face

## Data Description

Download the data here: [**Face Photos**](https://talhassner.github.io/home/projects/Adience/Adience-data.html)

The data for this project consists of several face photos.  They were collected from Flickr albums that contained photos automatically uploaded from people's smart phone devices and have since been released by the original owners.

The total number of photos in this dataset is 26,580 from 2,284 different subjects.  The images are of people from various different age groups which have been segmented into 8 different categories (0-2, 4-6, 8-13, 15-20, 25-32, 38-43, 48-53, 60+).

There are various files you can download from the data source.  The file relevant to this project are: 
* **faces.tar.gz** 
* **fold_0_data.txt - fold_4_data.txt**

The first file contains the actual images, whereas the second group of files lists all of the information collected on each photo.  The columns are as follows (Description taken from [here](https://talhassner.github.io/home/projects/Adience/readme.txt)):

* `user_id` - the folder in the dataset containing the image. 
* `original_image` - image name in the dataset.
* `face_id` - the Face ID in the original Flickr image, can be ignored. 
* `age` - age label of the face.
* `gender` - gender label of the face.
* `x`, `y`, `dx`, `dy` - bounding box of the face in the original Flickr image, can be ignored.
* `tilt_ang`, `fiducial_yaw_angle` - pose of the face in the original Flickr image, can be ignored. 
* `fiducial_score` - score of the landmark detector, can be ignored.



## Libraries

## Sources

[1] Eran Eidinger, Roee Enbar, Tal Hassner. Age and Gender Estimation of Unfiltered Faces. Transactions on Information Forensics and Security (IEEE-TIFS), special issue on Facial Biometrics in the Wild, Volume 9, Issue 12, pages 2170 - 2179, 2014. 

