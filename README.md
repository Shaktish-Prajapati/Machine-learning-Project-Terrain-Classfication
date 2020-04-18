# Satellite-Terrain-Classification
Satellite Terrain Classification
dataset:--  https://www.kaggle.com/crawford/deepsat-sat4

Get Input Data:-
The input data was encoded into CSV files.
The X_test_sat4.csv flattened the images that were 28 x 28 x 4 that were taken from space. 
The first three channels are the standard red, green, and blue channels in normal images. 
The 4th is a near-infrared band. We are using the smaller test set because the training set is too big.
After extracting the data from the csv files, we can reshape it into the original images. 
Then, we can see the images before we train on them. The second file we are loading are the labels for each image. 
They can be one of 4: barren land, trees, grassland and other. Each row in the file looks like this [1,0,0,0], where only one of the 4 value is 1.
If it is one, then it is that class respective to the order I showed above. If it was the above values, the image is a picture of barren land.
If it was [0,1,0,0], then it would be trees. If it was [0,0,1,0],then it would be grassland and so on.

My Work on the dataset:- https://www.kaggle.com/abhimanyuchauhan/satellite-image-classification?scriptVersionId=31652883

Code with output:- Terrain Classification.ipynb


Only Code:- Satelitte Image Classification.ipynb

This project was done in a group of two people:

Shaktish Prajapati                                              Abhimanyu Singh
11810947                                                        11800740

