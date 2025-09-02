# INFO8010 Deep Learning

## Authors
These projects were carried by:
- [Federico Ferraro](https://github.com/FreezieNinja)
- [Thibaut Lefèvre](https://github.com/THLefevre)
- [Duy Vu Dinh](https://github.com/duvuvu)

## Overview
Welcome to the GitHub repository for the projects of the INFO8010 course. 

## Homework 1
In this first homework, you will familiarize yourself with the basics of differentiable programming and the PyTorch framework. At the end of this assignment, you should be able to build and train your own multi-layer perceptron. Although this assignment is optional, we **strongly** advise you to do it as you are expected to be comfortable with PyTorch at the end of this course.

## Homework 2
In this homework we will see some slighly more complicated deep learning concepts: we will start by taking a look at some of PyTorch's functionalities that are necessary for training deep networks efficiently. We will then train our first neural networks for tackling different image classification tasks, learn to build custom datasets and explore how to train a CNN.

## Project
The goal of the course project was to tackle any kind of project which could be solved by any deep learning method, with an applicative perspective. We chose to work on image semgentation of footbal players, exploring different architectures based on U-Net.  
Semantic segmentation is a fundamental problem in computer vision, where the goal is to classify each pixel of an image into a predefined category. In this project, 
we implement and compare multiple deep learning architectures for semantic segmentation of football players, including **U-Net, TinyUNet, U-Net++, ResUNet**, and custom hybrid models. Trained on the [Football Player Segmentation dataset](https://www.kaggle.com/datasets/ihelon/football-player-segmentation), the models are evaluated using IoU, Dice score, and qualitative visualizations. Results show that advanced architectures like **ResUNet and custom ResUNet++** achieve the best performance, while lighter models such as TinyUNet offer efficiency trade-offs. All models are built from scratch in **PyTorch**, with preprocessing, augmentation, and reproducible training pipelines included.
