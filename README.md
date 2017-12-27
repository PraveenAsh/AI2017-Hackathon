# AI2017 Hackathon


Using the PASCAL VOC2010 dataset, build a classifier. We will build the classifier to classify 20 across classes using Keras, CNN based models.Perform detecting object localization : predict bounding box for each image.


**Download the dataset from:**
>Link 1 : [dataset](https://drive.google.com/open?id=1K2CuUPANucTAvTX_f7Qg7eN8kqBCA9oZ)
>
>Link 2 : [dataset](https://drive.google.com/open?id=1XNX2oqoJqa6wJAAhcetPOM6du9MT38r)
>
>This dataset is a part of a publicly hosted contest VOC2010 challenge. Please visit http://host.robots.ox.ac.uk/pascal/VOC/voc2010/ for
complete description of the different competition tasks and description of data.

*Two stages:*

**Classification and Detection**
Use the code from the devkit for dataset processing. But note that this is a MATLAB file and if you are required to develop it in python. 
Training, dev (validation) and test data. Split the given dataset in to train/validation/test datasets. Do not mix this up.

**Building Classifier**
Build a classifier using regular CNN with Keras.
Perform any image preprocessing, convert these to a uniform size.
Tune it and keep improving towards the best score.
Start with small size of dataset and gradually increase. Note that the training time for a complex CNN may take a few hours even on a high end machine. Use GPU based machines wherever you can. You should have installed TensorFlow GPU version and also CUDA libraries for GPU.
Measure the accuracy, precision, recall for each of the classifiers (20 classes) and report. Remove the top layers and replace them with a 20 layer Softmax. Please refer [keras] (https://keras.io/applications/).
