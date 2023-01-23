# Preprocessing data into images and analysing the image data

This repository includes files for preprocessing the data from the dataset attached i.e., TrainingData.csv

Initially, binary data is preprocessed and is converted into groups of bytes. These bytes are aggregated as a list. 

We observe that each data item, can be expressed as a list of 2000 bytes. So, an additional 25 bytes, each representing 255, are appended to make the total count of the list a perfect square. 

This is done to ensure that a gray scale image that can be generated from this list is a square image

These images so generated are used for classification
