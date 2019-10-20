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
