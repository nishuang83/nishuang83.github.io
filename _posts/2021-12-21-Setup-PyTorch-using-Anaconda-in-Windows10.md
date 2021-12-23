---
title: 'Setup PyTorch using Anaconda in Windows 10'
date: 2021-12-21
permalink: /posts/2021/12/Pytorch/
tags:
  - cool posts
  - category1
  - category2
---

# Setup PyTorch using Anaconda in Windows 10

### Author:Shuang

This blog is to give a tutorial of installing PyTorch in Windows 10 using [Anaconda](https://www.anaconda.com/). Before this tutorial, Anaconda should be installed in advance. 

## 1. Find a CUDA version compatible with your GPU
If you have a GPU in your computer, open NVIDIA control panel, click `System Information` and choose `conponents` to check the version of CUDA for your GPU. 

## 2. Setup PyTorch
### 2.1 Create an enviornmnet in Anaconda

### 2.2 Install PyTorch
Check the [PyTorch website](https://pytorch.org/get-started/locally/) to find the command to install the specific version of PyTorch. 
Choose "Stable", "Windows", "Conda", "Python" and the proper version of CUDA. If there's no avaliable GPU i your computer, choose CPU.
![PyTorch](https://github.com/nishuang83/nishuang83.github.io/blob/master/images/pytorch1.JPG)

Then, it shows a command and paste it into Anaconda Prompt. 
Press Enter and follow the instruction of Anaconda Prompt (usually only press y).

## 3. Run code with VScode or Anaconda Prompt
![VScodeRun](https://github.com/nishuang83/nishuang83.github.io/blob/master/images/post-images/2021-12-21-pytorch/VScodeRun.PNG)
