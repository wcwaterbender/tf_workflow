# TensorFlow Workflow
This guide is meant to be a resource for those who wish to delve into the realm of tensorflow and machine learning.

## 1. Data Preparation/Cleaning
Before building a model, data must be gathered, organized, and cleaned before it can be attached to an input pipeline for Tensorflow.

Detailed instructions on getting started can be found here:
https://cloud.google.com/ml-engine/docs/tensorflow/data-prep

## 2. Training, Evaluation, and Test Data
The next step to building a model is defining your 3 distinct subsets of data that you will be working with : Training Data, Evaluation Data, and Test Data.

See : https://cloud.google.com/ml-engine/docs/tensorflow/data-prep#split_the_data

## 3. Preprocessing Data
After Data has been gathered and cleaned, it must be preprocessed and standardized.

Preprocessing varies depending on the type of input for constructing a model.

For preprocessing images, an excellent example can be found here: https://www.tensorflow.org/programmers_guide/datasets#decoding_image_data_and_resizing_it


## 4. Creating Datasets to be used with Tensorflow
Once the data has been preprocessed and standardized, it can be attached to an input pipeline. A standard method involves the creation of Dataset objects containing records gathered from the data you preprocessed.The records are accessed with an Iterator object.

In-depth mechanics of the Dataset and Iterator objects can be found here: https://www.tensorflow.org/programmers_guide/datasets#basic_mechanics

## 5. 

