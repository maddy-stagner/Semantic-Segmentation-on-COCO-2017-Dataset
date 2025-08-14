# Semantic-Segmentation-on-COCO-2017-Dataset
Semantic Segmentation with U-Net on COCO-2017 Dataset

This repository contains a Jupyter notebook (CV3Q_MADHAV.ipynb) that implements a semantic segmentation model using the U-Net architecture on the COCO-2017 dataset, focusing on the classes "person," "cat," and "car." The notebook uses the FiftyOne library to load the dataset, trains a U-Net model, and evaluates its performance using Mean IoU and Dice Score metrics.

Project Overview

The project demonstrates a complete pipeline for semantic segmentation:





Dataset: Loads a subset of the COCO-2017 dataset (train split, 1000 samples) with annotations for "person," "cat," and "car" classes using FiftyOne.



Model: Implements a U-Net architecture using TensorFlow/Keras for semantic segmentation.



Training: Trains the model on the dataset with a train-validation split (80% train, 20% validation).



Evaluation: Computes performance metrics, including Mean IoU and Dice Score, on the validation set.



Visualization: Uses FiftyOne to visualize the dataset and predictions.

Prerequisites





Python 3.8 or higher



A system with sufficient storage (~150 GB for the COCO-2017 dataset)



GPU (recommended for faster training)
Repository Structure





CV3Q_MADHAV.ipynb: Main Jupyter notebook containing the semantic segmentation pipeline.



requirements.txt: List of Python dependencies.



.gitignore: Specifies files and directories to ignore in version control (e.g., dataset files, virtual environments).



README.md: This file, providing project documentation
Notes





Dataset Size: The COCO-2017 dataset is large. Ensure sufficient disk space and consider using a subset for testing (already limited to 1000 samples in the notebook).



Hardware: Training the U-Net model is computationally intensive. A GPU is recommended for reasonable training times.



FiftyOne App: The FiftyOne visualization app requires a web browser. Ensure you have a compatible browser and port access (default: 5151) if running remotely.

