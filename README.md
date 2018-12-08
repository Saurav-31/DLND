# DLND
Projects Related to Deep Learning Udacity Nanodegree

**Project 1: Neural Network from scratch**

Training on a bike rides dataset using a single hidden layer fully connected neural network.
Forward and Backward Propogation functions are written.
Losses for validation and training are also plotted.

**Project2: Image Classification On CIFAR-10 dataset**

A CNN model with three conv and max pool layers, initializations with truncated normal weights and finally two FC layers are trained from scratch. Conv, max pool and fc layers are mostly written using tensorflow.nn.layers without backward prop operations. Full training is done in tensorflow 1.4.0 + cuda-8.0 + cudnn-6.0

Accuracy ~ 53% for 30 epochs 
Batch Normalisation, data augmentation and hyperparamter tuning is not done yet.

**Project3: TVScriptGeneration from Simpson's scenes**

Tensorflow implementation of a LSTM network is used. 

Instructions to run: 
1. Create a new conda environment with 
    conda create -n tvscript python=3.5
2. Install all the packages required with 
    pip install -r requirements.txt
    pip install tensorflow-gpu==1.0.0

Use cuda-8.0 + cudnn6

**Project4: Language Translation from English to French Sentences"

Results are quite good. Use the same configuration which was used for Project3. tesnorflow1.0.0 + cuda-8.0 + cudnn6

**Project5: Generate Celeb Faces using GAN's **

Uses a model that do well to generate digits when trained on Mnist dataset and then use the same model with more number of Layers with Generator and discriminator network.




