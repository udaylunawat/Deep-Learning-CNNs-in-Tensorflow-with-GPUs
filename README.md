Deep-Learning-CNNs-in-Tensorflow-with-GPUs

With this model forked from "TensorBoard-TF-Dev-Summit-Tutorial-master" I learned the architecture of a convolutional neural network (CNN), how to create a CNN in Tensorflow, and provided predictions on labels of images. Also, I learned how to run the model on a GPU so as to spend my time creating better models and not waiting for them to converge.

Overview

    Introduction to CNN’s
    Creating your first CNN and training on CPU
    Training on a GPU
    
https://hackernoon.com/deep-learning-cnns-in-tensorflow-with-gpus-cba6efe0acc2

I trained the model on my CPU i5-4440 (3.10 GHz default clock speeds)
![cpu](https://user-images.githubusercontent.com/24354945/31680579-620d5dfe-b392-11e7-8d58-4a3f1ebbb48f.PNG)

The image below shows that the training (with CPU) started at 12:22:28
![cpu training started](https://user-images.githubusercontent.com/24354945/31680578-61cb6ae8-b392-11e7-90c5-a0a2f323e113.PNG)

And finished at 12:52:12 (about 30 minutes later)
![cpu training finished](https://user-images.githubusercontent.com/24354945/31680577-6156aba4-b392-11e7-86f6-6e9f330fc494.PNG)

To test Deep Learning on GPU i used a GTX 1060 3 GB from Zotac (Single fan) at stock speeds
Training Started at 11:58:37 and completed in just about 5 minutes at 12:03:47
that is a mid-range GPU is 6 times faster than a 4th generation i5. ( in case of MNIST)
![mnistgpu](https://user-images.githubusercontent.com/24354945/31680580-6256b85a-b392-11e7-834f-a199d29ffa8b.PNG)

But the usage and temperature reports show that the GPU was only utilised at max 30% and could've been faster.
![usagereportgputraining](https://user-images.githubusercontent.com/24354945/31680582-629dac92-b392-11e7-8c8f-e6a1cd1c7251.PNG)
