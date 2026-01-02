# DBSCAN Clustering Demonstration
## BY Ribka Mengiste            UGR/9680/15        Software-Stream

## Overview
This repository contains a demonstration of the **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm as part of a Machine Learning clustering assignment.  
The notebook is designed to follow the same structure and experimental flow as the K-Means clustering lab 

## Contents
- `DBSCAN.ipynb` – Complete DBSCAN clustering demonstration

## Description
The notebook applies DBSCAN to multiple datasets, including:
- Spherical blob data
- Non-linear datasets (moons and circles)
- High-dimensional data with PCA-based visualization

Standard scaling is applied prior to clustering to ensure distance-based consistency.  
The effect of DBSCAN parameters (`eps` and `min_samples`) is also explored.

## Key Observations
- DBSCAN does not require predefining the number of clusters
- It effectively detects noise and outliers
- It performs well on non-spherical and irregular cluster shapes
- Parameter selection significantly impacts clustering results

## Requirements
- Python 3.x
- scikit-learn
- numpy
- matplotlib


Machine Learning Assignment 
