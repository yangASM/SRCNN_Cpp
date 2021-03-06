# SRCNN_Cpp (Old Version: IplImage)
C++ Implementation of Image Super-Resolution using Convolutional Neural Network

### Introduction
**SRCNN_Cpp** is a C++ Implementation of Image Super-Resolution using SRCNN which is proposed by Chao Dong in 2014.
 - If you want to find the details of SRCNN algorithm, please read the paper:  

   Chao Dong, Chen Change Loy, Kaiming He, Xiaoou Tang. Learning a Deep Convolutional Network for Image Super-Resolution, in Proceedings of European Conference on Computer Vision (ECCV), 2014
 - If you want to download the training code(caffe) or test code(Matlab) for SRCNN, please open your browse and visit http://mmlab.ie.cuhk.edu.hk/projects/SRCNN.html for more details.
 - And thank you very much for Chao's work in SRCNN.

### License
SRCNN_Cpp is released under the GPL v2 License (refer to the LICENSE file for details).

### Contents
1. [Requirements](#requirements)
2. [Demo](#demo)

### Requirements

1. You need to install *OpenCV2+* or *OpenCV3+* in your computer.

   OpenCV download site: http://opencv.org/

2. You also need to install *pkg-config*.

3. And we really need *g++* which is already installed in almost all Linux systems.

**Note:** we do not need *Caffe* in your system!   

Our *SRCNN_Cpp* is developed in fc22 x64_86 system with g++-5.3 and OpenCV 3.0.0.

### Demo

You can compile the C/C++ files on the command line in your Linux system. And the program will execute automatically.

``` Shell
$ ./opencv.sh SRCNN
```

Enjoy yourself~
