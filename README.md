# Introduction
In this notebook, I have built a deep neural network that functions as part of an end-to-end machine translation pipeline. The completed pipeline will accept English text as input and return the French translation.

# Setup

This project requires GPU acceleration to run efficiently. Support is available to use either of the following two methods for accessing GPU-enabled cloud computing resources.


## Amazon Web Services (Optional)

Please refer to the given instructions for setting up a GPU instance for this project, and refer to the project instructions in the classroom for setup. The recommended AMI should include compatible versions of all required software and libraries to complete the project. [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)

## Install
- Python 3
- NumPy
- TensorFlow 1.x
- Keras 2.x

## Dataset
We begin by investigating the dataset that will be used to train and evaluate your pipeline.  The most common datasets used for machine translation are from [WMT](http://www.statmt.org/).  However, that will take a long time to train a neural network on.  We'll be using a dataset we created for this project that contains a small vocabulary.  We'll be able to train our model in a reasonable time with this dataset.
