# machinelearning_assessment
Assessment for Machine Learning Module using Boston Housing Dataset. The goal was to describe, infer and predict using the dataset. The Boston Housing Dataset is a well known dataset in relation to housing in the Boston Metropolitan area. The dataset consists and of 13 variables and the data will be explored using desciptive statisticas and plots. There is also a linear regression model produced using two of the varibales. The CHAS varibale will also be discussed in relation to house prices.

## Installation and Running

This project was run on Pyhton version: 3.6.3 |Anaconda custom (64-bit)| (default, Oct 15 2017, 03:27:45) [MSC v.1900 64 bit (AMD64)]
This can be downloaded and installed on https://www.anaconda.com/<br>

The data is presented on a Jupyter Notebook.
Jupyter can be downloaded on http://jupyter.org/install. * note downloading python first is a prerequisite.<br>

Keras is used for data modelling.
More information about keras and how to install from the command line can be found on https://keras.io/

The dataset can also be found at http://lib.stat.cmu.edu/datasets/boston

## The Data

There is a high correlation interconnected between a lot of the variables. The data also has a large variance in scale and all this had to be taken into account when planning a prediction model. Various summary and descriptive wer used to show these traits.

## The Keras Model

I found it challenging to find suitable variations of the model to improve prediction error. There are so many options using the keras package that although these are fun to use the simple act of adding a few neurons to the layer can change the results dramatically!:grinning: Even after trying different standardising options the results could vary considerably using the same model for each run.<br> 
There are quite alot of activation options and I found relu was the most consistent. Overall standardizing and whitening the data did make the results more consistent.   

Author: Greg Feeley.
