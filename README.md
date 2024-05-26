# Image Classification Models using Tensorflow, Donkey vs Zebra vs Horse

## Description About Project

This project demonstrates how to build an image classification model usingTensorFlow. This model can classify three categories (“donkey”, “zebra”, or “horse”). This model is built by utilizing Image Augmentation and Transfer Learning. A pre-trained TF2 SavedModel from TensorFlow Hub is used for Transfer Learning.

## Infrastructure for Built Model

### Libraries

Model Machine Learning built with Jupyter Notebook on Google Colab. This Jupyter Notebook also can run in local. For development, the following are libraries which needs to be installed.

```
opendatasets==0.1.22

tensorflow==2.15.0
keras==2.15.0
tensorflow_hub==0.16.1

matplotlib==3.7.1
numpy==1.25.2

```

### Dataset

The data used to build this model was obtained from Kagle, that is [Donkeys, Horses &amp; Zebra Images Dataset](https://www.kaggle.com/datasets/ifeanyinneji/donkeys-horses-zebra-images-dataset).

### Pre-trained Model

Pre-trained model that used in this project can be accsesed [here](https://tfhub.dev/google/imagenet/efficientnet_v2_imagenet21k_b0/feature_vector/2). This is pre-trained TF2 SavedModel from TensorFlow. The SavedModel format of TensorFlow 2 is the recommended way to share pre-trained models and model pieces on TensorFlow Hub.

Source: 

* [https://www.tensorflow.org/hub/lib_overview](https://www.tensorflow.org/hub/lib_overview)
* [https://www.tensorflow.org/hub/tf2_saved_model](https://www.tensorflow.org/hub/tf2_saved_model)
* [https://www.tensorflow.org/hub/lib_overview](https://www.tensorflow.org/hub/tutorials/tf2_image_retraining?hl=id#select_the_tf2_savedmodel_module_to_use)

## How to Use This Project

For using this project you must clone this machine learning project with following command. 

`https://github.com/fawwazmts/image-classification-tf-donkey-zebra-horse.git`

### How to Build Models

Complete steps on how to build the model are available on [image_classification_tf_donkey_zebra_horse.ipynb](https://github.com/fawwazmts/image-classification-tf-donkey-zebra-horse/blob/main/image_classification_tf_donkey_zebra_horse.ipynb). A summary of the steps is as follows.

1. Get [Donkeys, Horses &amp; Zebra Images Dataset](https://www.kaggle.com/datasets/ifeanyinneji/donkeys-horses-zebra-images-dataset) from Kagle.
2. Merge again datasets.
3. Split againdatasets into train, validation, and test datasets.
4. Train model with data by utilizing .
