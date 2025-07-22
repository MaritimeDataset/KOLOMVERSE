# KOLOMVERSE

This is a repository that contains links to the KOLOMVERSE dataset and codes to train and reproduce results of the paper titled "KOLOMVERSE: Korea Open Large-Scale Image Dataset for Object Detection in the Maritime Universe". 
 <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig4-2.png">


# Overview
KOLOMVERSE is a large-scale object detection dataset in the maritime domain. It has a total of 186,419 4K resolution images categorized into 5 different
classes namely ship (393,936 instances), buoy (34,080 instances), fishnet buoy (95,815 instances), lighthouse (60,362 instances) and wind farm (147,846 instances). The dataset is collected from 21 territotial waters of South Korea and is split in to train (49,175 images), validation (18,643 images) and test (18,601 images) sets.

# Dataset Download
If you wish to download the KOLOMVERSE dataset along with the associated codes and scripts, please fill out this [Google request form](https://docs.google.com/forms/d/e/1FAIpQLSexxqTdY32CKhYBSP7r8c8RiKN7NHUf8PLtAMBXBD4rL9TxmA/viewform?usp=dialog).  
Once approved, we will email you the download link.

If you use the KOLOMVERSE dataset in your research, please cite the following paper:

```bibtex
@ARTICLE{10689331,
  author    = {Nanda, Abhilasha and Cho, Sung Won and Lee, Hyeopwoo and Park, Jin Hyoung},
  title     = {KOLOMVERSE: Korea Open Large-Scale Image Dataset for Object Detection in the Maritime Universe},
  journal   = {IEEE Transactions on Intelligent Transportation Systems},
  year      = {2024},
  volume    = {25},
  number    = {12},
  pages     = {20832-20840},
  doi       = {10.1109/TITS.2024.3449122},
  keywords  = {Object detection;Safety;Boats;Wind speed;Wind farms;Object recognition;Global Positioning System;Marine navigation;Maritime domain;large-scale image dataset;object detection;maritime safety}
}
```


# Dataset Statistics

Distribution of train-test-validation split in the 21 territories of KOLOMVERSE. <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig19.png">
The KOLOMVERSE images are categorized into 5 different
classes namely hip (393,936 instances), buoy (34,080 instances), fishnet buoy (95,815 instances), lighthouse (60,362 instances) and wind farm (147,846 instances). <img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig4-1.png">

# Variations in the dataset
KOLOMVERSE has variations in illumination, viewpoint, occlusion, background, scale and proportion that makes object detectors trained
with KOLOMVERSE more suitable for real time applications.

Image samples with illumination variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig16(2).png">

Image samples with occlusion variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig11.png">

Image samples with backgorund variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig15(2).png">

Image samples with viewpoint variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig10.png">

Image samples with proportion variation: 
<img src= "https://github.com/kmdMaritimeDataset/KMD-Maritime-Dataset/blob/main/Images/Fig12.png">


