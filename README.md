#Dendritic_Spine_Detection-Analysis
A machine learning approach to detecting and analyzing dendritic spines.

This project leverages a Convolutional Neural Network (YOLOv9) to accurately detect dendritic spines in microscopy images. After detection, a custom algorithm is used to measure the distance from each spine to its corresponding dendrite segment, label the distances, and calculate the surface area of each spine. Additionally, the project includes computations for the length of each dendrite and determines the density of spines per millimeter.

Features:
Spine Detection: Utilizes YOLOv9 for precise identification of dendritic spines.
Distance Measurement: Custom algorithm calculates the length from each spine to the dendrite segment.
Surface Area Calculation: Computes the surface area of each detected spine.
Dendrite Length Analysis: Measures the total length of dendrites in the sample.
Spine Density: Determines the number of spines per millimeter of dendrite.
This repository provides the tools and code necessary for advanced analysis of dendritic structures, enabling deeper insights into neuronal morphology.
