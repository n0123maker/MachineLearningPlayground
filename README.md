# Tensorflow GPU

TensorFlow GPU support requires an assortment of drivers and libraries.

##### The following NVIDIA® software must be installed:
* NVIDIA® GPU Drivers
    ```
    436.15-notebook-win10-64bit-international-whql.exe
    ```
* CUDA® Toolkit
    ```
    cuda_10.1.243_426.00_win10.exe
    ```
* cuDNN SDK
    ```
    cudnn-10.1-windows10-x64-v7.6.2.24.zip
    ```
    Extract archive to:
    ```
    C:\tools\
    ```

##### Add the CUDA, CUPTI, and cuDNN installation directories to the %PATH% environmental variable.
```
C:\> SET PATH=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.0\bin;%PATH%
C:\> SET PATH=C:\Program Files\NVIDIA GPU Computing Toolkit\CUDA\v10.0\extras\CUPTI\libx64;%PATH%
C:\> SET PATH=C:\tools\cuda\bin;%PATH%
```

Reference: https://www.tensorflow.org/install/gpu

# Course Material

## CS189/289A: Introduction to Machine Learning (Berkeley)
https://people.eecs.berkeley.edu/~jrs/189/

Prerequisites:

Linear Algebra: http://cs229.stanford.edu/section/cs229-linalg.pdf

Probability Theory: http://cs229.stanford.edu/section/cs229-prob.pdf

Math for Machine Learning: http://gwthomas.github.io/docs/math4ml.pdf

## CS231n: Convolutional Neural Networks for Visual Recognition | Spring 2019
http://cs231n.stanford.edu/

## CS224n: NLP with Deep Learning, Stanford | Winter 2019
http://web.stanford.edu/class/cs224n/

## CS285: Deep Reinforcement Learning, UC Berkeley | Fall 2019
http://rail.eecs.berkeley.edu/deeprlcourse/

## Textbooks

An Introduction to Statistical Learning with Applications in R

http://www-bcf.usc.edu/~gareth/ISL/

Videos: https://www.r-bloggers.com/in-depth-introduction-to-machine-learning-in-15-hours-of-expert-videos/

The Elements of Statistical Learning - Data Mining, Inference and Prediction

https://web.stanford.edu/~hastie/ElemStatLearn/

## Nvidia Deep Learning Institute

https://www.nvidia.com/en-us/deep-learning-ai/education/

## Awesome Deep Learning

https://github.com/ChristosChristofidis/awesome-deep-learning

## Data Science Cheat Sheet

https://github.com/abhat222/Data-Science--Cheat-Sheet
