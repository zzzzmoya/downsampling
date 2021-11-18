# Project Title

Downsampling select representative dataset 

## Description

Pipeline of select representative image dataset from a large dataset using 2 different approach: unsupervised(VGG) and traditional CV(ORB). 

## Pipeline structure:
* Feature extraction using traditional approach(ORB) -> Bag of Feature on image features with k-means -> PCA dimention reduction -> k-means clustering
* Feature extraction using CNN approach(VGG) ->  PCA dimention reduction -> k-means clustering
## Getting Started

### Dependencies
* Python 3
* Tensorflow

### Installing

* Pull from the github page with the link from clicking 'Code' then clone
* pip install all dependency packages

## Authors

* Moya Zhu (uni: mz2886) MSDS 22'
Worked with Fairvision research group
