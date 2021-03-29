# COVID-19 X-Ray Classification

## Introduction

The goal of this project was to create Convulutional Neural Networks using Tensorflow/Keras to properly and accurately predict whether an X-ray image has COVID-19, pneumonia, or nothing at all.

## Dataset
URL: "https://www.kaggle.com/pranavraikokte/covid19-image-dataset"

## Model

We used a Sequential model with 1 hidden layer, and used Categorical Crossentropy to measure our loss.

Model had ~5,000 parameters (in order to keep runtime low)

## Results

Though the accuracy was high, the precision, recall, and F1 scores told a different story. See conclusion section in notebook for details.
