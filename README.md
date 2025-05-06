# AlpinePlantID-MobileNetV1
Title: "Optimized MobileNet V1 with Efficient Channel Attention for Accurate Alpine Grassland Plant Identification"

The paper is currently being submitted to the journal The Visual Computer with the following citation format: Zhang, T., Yao, H., Zhao, Y. et al. Optimized MobileNet V1 with Efficient Channel Attention for Accurate Alpine Grassland Plant Identification. Vis Comput(2025)

![fig5](https://github.com/user-attachments/assets/8c869d39-1b3a-4be8-8e4b-c6d1eee1aaac)


This study aims to systematically evaluate the performance of different attention mechanisms (SE, CA, CBAM, ECA) in combination with various backbone networks (MobileNetV1/V2/V3, VGG16/19, ResNet152v2) for plant image classification tasks using deep learning methods. By constructing a unified experimental framework and conducting ablation studies, the specific contributions of each attention module to feature extraction and classification accuracy enhancement are quantitatively analyzed.

To facilitate researchers and developers in reproducing the experimental workflow and evaluating model performance, we provide comprehensive documentation for the open-source code of this project, as detailed below:

## 1.Usage Guide

### Project Structure Description:

The project files are organized by three main directories: code, data, and result. 
The code folder contains three subdirectories: Original_Model, Attention_Mechanism, and Ablation_Experiment, each corresponding to the baseline networks, attention modules, and ablation studies, respectively. 
The data folder includes a readme.txt file with dataset information. 
The result folder mirrors the structure of the code directory with matching subdirectories to store the corresponding experimental outcomes for each module of the project.

### Running Environment:
Operating System: Ubuntu 22.04.2
Python Version: 3.8 or above
GPU: NVIDIA RTX 4090 24GB × 1
CPU: 12 cores
RAM: 96 GB
Storage: 50 GB system disk, 200 GB data disk
Network: 20M public network bandwidth
Supported deep learning frameworks: TensorFlow 2.15 / PyTorch 12.2 / CUDA 3.11

## 2.Dependencies

This study primarily relies on the following third-party libraries: numpy; matplotlib; tensorflow or torch; opencv-python; scikit-learn; seaborn


## 3.Key Algorithms

### Attention Mechanism Modules:

SE（Squeeze-and-Excitation）；CA（Coordinate Attention）；CBAM（Convolutional Block Attention Module）；ECA（Efficient Channel Attention）

### Backbone Networks:

MobileNetV1/V2/V3, ResNet152v2, and VGG16/19 are all loaded with ImageNet pre-trained weights and integrated with attention modules for transfer learning.

### Training and Evaluation:


All models support a unified training interface and provide multi-dimensional performance evaluation, including accuracy, F1 score.



## 4.Reproducibility

All experiments can be reproduced by running the specified .ipynb files, which include model definitions, training procedures, and visualization analyses.

Each notebook is well-commented to facilitate understanding and customization.

Classification results are uniformly saved in the result folder for easy comparison and analysis.

## 5.datesets: zenodo
Our datasets can be available at https://doi.org/10.5281/zenodo.12819920.

#### For assistance or project demonstrations, please contact the author via email: zt3274422972@163.com
