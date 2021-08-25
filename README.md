# Saree-detection
## Problem statement


To identify different parts of a saree and to identify it's color , border , textile material 

## Objective of this project 

To Create a simple code without any machine learning algorithms (if possible)

## Current state of progress 

### Data set 

colors.csv 

Dataset - Images of saree 

### Code

color detection.ipynb   **-( jupyter notebook extension )**

### Description 

In the current state of the model I am trying to identify the color of the overall saree , the basic idea of this code is to extract the RGB array from the image and to match it with the colour.csv database and display the result accordingly .

## Future work 

To Perform data annotation and the label it according to the 3 sections . 

### Colore Detection 

To Create a bounding box which will display the main part of the saree and to take the average value of all the RGB arrays inside the bounding box and to follow the same process shown in color detection.ipynb code 

### saree border detection 

To Create a Bounding box which will identily the border in the saree . To Train a tiny model which exixting dataset of saree borders which will help in identifying  the boarder types . 



## Reference 

https://towardsdatascience.com/ai-for-textiles-convolutional-neural-network-based-fabric-structure-classifier-c0db5433501d


https://www.hindawi.com/journals/mpe/2020/8189403/


https://www.geeksforgeeks.org/multiple-color-detection-in-real-time-using-python-opencv/


https://emerj.com/ai-sector-overviews/artificial-intelligence-in-the-textile-industry-current-and-future-applications/




