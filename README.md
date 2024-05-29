# Instance Segmentation using Mask R-CNN on Chemistry Lab Images

This project demonstrates instance segmentation using Mask R-CNN, one of the pioneering algorithms for instance segmentation. The implementation utilizes a pre-trained Mask R-CNN model on the ChemistryLabPics dataset.

Table of Contents

    •	Overview
    •	Dataset
    •	Methodology
               Model
               Feature Extraction
    •	Results
    •	Libraries Used

Overview

    In this project, instance segmentation is performed using the Mask R-CNN algorithm. The pre-trained Mask R-CNN model is fine-tuned on the ChemistryLabPics dataset to accurately identify and segment various objects found in a chemistry lab, such as vessels, flasks, jars, test tubes, and more.
Dataset

    The dataset used in this project is the ChemistryLabPics dataset, which can be found here.
Methodology

    Model
        •	Mask R-CNN: A powerful instance segmentation algorithm that extends Faster R-CNN by adding a branch for predicting segmentation masks on each Region of Interest (RoI), in parallel with the existing branch for classification and bounding box regression.
        •	Fast R-CNN: Used for box prediction in the last layer of the model.
    Feature Extraction
        •  Backbone Algorithm: Feature Pyramid Network (FPN)
          	  Architecture: Bottom-up architecture with a pre-trained ResNet model and Convolutional Neural Networks (CNNs).
Results

    The model provided accurate results for masking the instances and overall identification of chemistry lab images, successfully detecting objects like vessels, flasks, jars, test tubes, and more.
Libraries Used

    •	PyTorch: Used for implementing the model and performing instance segmentation.


you can find the dataset from the link below

    https://www.kaggle.com/datasets/sagieppel/labpics-chemistry-labpics-medical
