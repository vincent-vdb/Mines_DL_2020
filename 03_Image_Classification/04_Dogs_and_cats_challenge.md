# Challenge - Dogs and Cats

## Guidelines

This challenge is a famous one about dogs and cats classification.

See Kaggle dataset dogs and cats [here](https://www.kaggle.com/c/dogs-vs-cats) if you want to download the full dataset. For simplicity, we here provide a subsample of 1200 dogs and 1200 cats images in `dogs_cats.zip`.

Here you will use a very useful tensorflow tool: the image data generator. You can have a look at the documentation [here](https://www.tensorflow.org/api_docs/python/tf/keras/preprocessing/image/ImageDataGenerator). It will deal for you with the labels as well as the image resizing automatically.

### Data Preparation
We propose to use only a subset of the training dataset for computing resources reasons: 1000 cats + 1000 dogs images in train, 200 cats + 200 dogs in test.

First split by hand your dataset like the following:
```
- data/
--- train/
----- cats/
------- cats1.jpg
------- cats2.jpg
        ...
------ dogs/
------- dogs1.jpg
------- dogs2.jpg
        ...
--- test/
----- cats/
------- cats1001.jpg
------- cats1002.jpg
        ...
----- dogs/
------- dogs1001.jpg
------- dogs1002.jpg
        ...
```

### Data exploration

Feel free to open and display some images.

### Model building

Build a Convolutional Neural Network.

### Model training

Use the `ImageDataGenerator` to train your model on the data.

### Performances estimation

Estimate the performances of your model with the accuracy metrics. Is it good enough? 

Then try to improve by all means you can leverage: architecture, hyperparameters, transfer learning, data augmentation...