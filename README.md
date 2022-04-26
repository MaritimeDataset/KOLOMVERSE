(This page is under construction.)
This is a repository that contains codes to train and reproduce results of the paper submitted to Datasets and Benchmarks Track of NeurIPS 2022 titled "KMD: A large-scale public dataset for maritime object detection". 

# KMD-Maritime-Dataset
KMD is a large-scale object detection dataset in the maritime domain. It has a total of 2,151,470 4K resolution images categorized into 5 different
classes namely ship (3,791,372 instances), buoy (67,048 instances), fishnet buoy (273,051 instances), lighthouse (103,358 instances) and wind farm (338,673 instances). The dataset is collected from 21 territotial waters of South Korea and is split in to train (1,729,601 images), validation (211,038 images) and test (210,831 images) sets.

# Dataset Download
To run the object detectors for training and evaluation, you must first download the dataset and unrar/unzip it in the home folder of this project. The dataset can be acquired after filling this google form  [Link}] https://docs.google.com/forms/d/e/1FAIpQLScaZT7D7nSwNR9n2rco4FaoqEvQQVR9PreNnn92PIxxWlSD4g/viewform. Once we have your information like email ID and purpose of using our dataset, we shall mail you the link to download our dataset.

# Explanation of codes and scripts
(This part is under construction.)

# Dataset Statistics
This portion explains KMD dataset statistics.

Distribution of train-test-validation split in the 21 territories of KMD. <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig19.png">
The KMD images are categorized into 5 different
classes namely ship (3,791,372 instances), buoy (67,048 instances), fishnet buoy (273,051 instances), 
lighthouse (103,358 instances) and wind farm (338,673 instances). <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig4-1.png"> <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig4-2.png">

# Variations in the dataset
KMD has variations in illumination, viewpoint, occlusion, background, scale and proportion that makes object detectors trained
with KMD more suitable for real time applications.

Image samples with illumination variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig16(2).png">

Image samples with occlusion variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig11.png">

Image samples with backgorund variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig15(2).png">

Image samples with viewpoint variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig10.png">

Image samples with proportion variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Fig12.png">


