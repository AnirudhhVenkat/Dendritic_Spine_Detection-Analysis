# Dendritic_Spine_Detection-Analysis
A machine learning approach to detecting and analyzing dendritic spines.

This repository contains Jupyter notebooks and accompanying datasets designed to detect dendritic spines in microscopy images and analyze their characteristics using machine learning.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Datasets](#datasets)
3. [Installation and Setup](#installation-and-setup)
4. [File Structure](#file-structure)
5. [Usage](#usage)
6. [Model Training](#model-training)
7. [Results](#results)
8. [Contributing](#contributing)
9. [License](#license)

## Project Overview

### Dendritic Spine Detection and Analysis
The `detection_and_analysis.ipynb` notebook leverages a Convolutional Neural Network (YOLOv9) to accurately detect dendritic spines in microscopy images. Post detection, the notebook employs a custom algorithm to:

- **Distance Measurement:** Calculate the length from each detected spine to its corresponding dendrite segment.
- **Surface Area Calculation:** Compute the surface area of each spine.
- **Dendrite Length Analysis:** Measure the total length of dendrites in the sample.
- **Spine Density Analysis:** Determine the density of spines per micrometer of dendrite.

These analyses provide a comprehensive understanding of the structural characteristics of dendritic spines.

## Datasets
- **Data Availability:** The dataset is available here: https://universe.roboflow.com/work-qfeh4/spines-kw7n6.
- **Training Data:** The datasets used for training the YOLOv9 model are microscopy images labeled with dendritic spine locations.
- **Test Data:** Additional microscopy images used to evaluate the model’s performance in detecting and analyzing dendritic spines.

## Installation and Setup

To set up this project, follow these steps:

1. Clone this repository:
    ```bash
    git clone https://github.com/YourUsername/Dendritic_Spine_Detection-Analysis.git
    cd Dendritic_Spine_Detection-Analysis
    ```

2. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Install Jupyter notebook or VS Code with the Jupyter extension.

## File Structure

```plaintext
├── detection_and_analysis.ipynb
├── README.md
└── requirements.txt
