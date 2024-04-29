# Ensemble-Deep-Learning-for-the-Detection-of-COVID-19-in-Unbalanced-Chest-X-ray-Dataset
<p align="justify">The goal of this project is to classify the COVID-19 from normal and pneumonia on Chest X-rays in unbalanced data distribution setting.         
This GitHub repository serves as the source code for a published paper in https://doi.org/10.3390/app112210528</p>



## Overview
 <p align="justify">
       We demonstrates ensemble deep learning to classify COVID-19, viral pneumonia and normal on unbalanced chest X-rays dataset. Initially, we preprocessed andsegmented the lung regions usingDeepLabV3+ method, and subsequently cropped the lung regions. The cropped lung regions were used as inputs to several deep convolutional neural networks (CNNs) for the prediction of COVID-19. The dataset was highly unbalanced; the vast majority were normal images, with a small number of COVID-19 and pneumonia images. To remedy the unbalanced distribution and to avoid biased classification results, we applied five different ap-proaches:     (i) balancing the class using weighted loss;    (ii) image augmentation to add more images to minority cases;    (iii) the undersampling of majority classes;    (iv) the oversampling of minority classes; and     (v) a hybrid resampling approach of over-sampling and undersampling. The best-performing methods from each approach were combined as the ensemble classifier using two voting strategies. Finally, we used the saliency map of CNNs to identify the indicative regions of COVID-19 biomarkers which are deemed useful for interpretability.
</p>

## Table of contents
* [Introduction ](#introduction) 
* [Software Requirements](#software-requirements) 
* [Data](#data) 
* [Getting Started](#getting-started)
* [Running Matlab files](#running-matlab-files)
* [Running Python Jupyter Notebooks](#running-python-jupyter-notebooks)
* [Classify Chest Xrays Images](#classify-chest-xrays-images)
* [Project Results](#project-results)
* [Link to the Publication](#link-to-the-publication)
* [Authors](#authors)
* [Project Motivation](#project-motivation)
* [References](#references)
