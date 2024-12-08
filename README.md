# FHR and UC Analysis & Image Segmentation Model Project

## Overview

This project addresses two distinct tasks:

1) FHR and UC Analysis: Analysis of Fetal Heart Rate (FHR) and Uterine Contraction (UC) data for insights using Python-based data visualization and signal processing techniques.

2) Image Segmentation Model: Development of an image segmentation model on a chosen dataset to identify and segment distinct regions within images using machine learning or deep learning techniques.

## Problem Statement 1: FHR and UC Analysis

## Objective

To analyze the FHR and UC dataset by:

1) Visualizing FHR and UC data through graphs.
2) Calculating the average FHR over epochs using beats per minute and pulse intervals.
3) Detecting peaks in the UC data to determine their durations and average the wider peaks.

## Dataset Description

Frequency: Data points recorded every 250 milliseconds.

Fields:

^ Time (ms): Elapsed time in milliseconds since recording started.
^ FHR (bpm): Fetal heart rate measured in beats per minute.
^ UC (TOCO): Numerical representation of uterine contractions.

## Tasks

1) Graphs:
^ Time vs FHR
^ Time vs UC

2) FHR Analysis:
^ Divide data into 3.75-second epochs and calculate average FHR in bpm and pulse intervals.

3) UC Peak Detection:
^ Identify peaks using scipy and measure peak widths.
^ Count peaks with widths exceeding 30 seconds and calculate their average duration.

## Deliverables

^ Plots for FHR and UC.
^ Detailed FHR analysis over epochs.
^ Peak detection analysis for UC, including counts and average durations.
^ Python code for all tasks.

# Problem Statement 2: Image Segmentation Model

## Objective

Develop an image segmentation model to accurately identify and isolate regions in images.

## Approach

1) Dataset: Use or generate a dataset for segmentation tasks (e.g., medical images, satellite imagery).

2) Model:
^ Options include traditional techniques (thresholding, edge detection) or deep learning models (e.g., U-Net, Mask R-CNN).

3) Evaluation:
^ Use metrics like IoU (Intersection over Union) or Dice Coefficient.

4) Visualization:
Compare original images with segmented outputs to validate performance.

## Deliverables
^ Model and training code.
^ Evaluation metrics and results.
^ Visualization of segmentation outputs.
# FHR-and-UC-Analysis-Image-Segmentation-Model-Project
# FHR_UC_Analysis_Image_Segmentation
# FHR_UC_Analysis_Image_Segmentation
