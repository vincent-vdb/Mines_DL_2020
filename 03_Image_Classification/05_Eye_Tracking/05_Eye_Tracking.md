# Eye Tracking

## Guidelines

### Introduction

In this challenge, you have two folders:
* `data/open`
* `data/close`

In those two folders, are present images of eyes, either opened or closed. You will have two main tasks:
* Classification: make a classifier that predicts if the eye is opened or closed using `close` and `open/train`
* Regression: make a regression that predicts the center of the pupil on `open/train` and test on `open/test`

Before doing so, you have to handle properly the images.

### Data Exploration
First, look at the data, open an image, display it, convert it to an array.

### Classification

Your first task will be to make a classifier that detects either an eye is closed or not based on a picture.

### Regression

Your second task will be to predict the center of an eye using regression, using the target values into the file `data/open/dataPupilCenter.csv`

