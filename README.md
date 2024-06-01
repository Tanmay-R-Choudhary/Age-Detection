# Age-Detection

## Dataset
I used the UTK Face dataset that is available on Kaggle for free. UTKFace dataset is a large-scale face dataset with long age span (range from 0 to 116 years old). The dataset consists of over 20,000 face images with annotations of age, gender, and ethnicity. The images cover large variation in pose, facial expression, illumination, occlusion, resolution, etc.

https://www.kaggle.com/datasets/jangedoo/utkface-new

## Model

I used a Convolutional Neural Network to train an AI model to detect 3 classes: young, middle, old. I got an accuracy of 75% in the validation dataset. I used Tensorflow, Keras, Pandas, and Sci-kit learn to train the model and prepare the training data.
