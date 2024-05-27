# Covid-19 Time Series Analysis and Fashion MNIST Compression

This repository contains two projects: one focusing on Covid-19 data analysis and the other on image compression using PCA with the Fashion MNIST dataset.

## Table of Contents

- [Overview](#overview)
- [Project 3A: Covid-19 Data Reporting](#project-3a-covid-19-data-reporting)
  - [Part 1: Time Series Analysis](#part-1-time-series-analysis)
  - [Part 2: PCA and Eigenvalue Analysis](#part-2-pca-and-eigenvalue-analysis)
  - [Part 3: Data Reconstruction](#part-3-data-reconstruction)
- [Project 3B: Fashion MNIST Compression](#project-3b-fashion-mnist-compression)
  - [Part 1: Getting Started](#part-1-getting-started)
  - [Part 2: PCA Compression](#part-2-pca-compression)
- [Usage](#usage)
- [Installation](#installation)
- [Contributing](#contributing)
- [License](#license)

## Overview

This repository contains implementations of two data analysis projects:
- **Project 3A:** Analyzes Covid-19 time series data to understand trends in different countries.
- **Project 3B:** Utilizes PCA for image compression on the Fashion MNIST dataset.

## Project 3A: Covid-19 Data Reporting

### Part 1: Time Series Analysis

Part 1 of Project 3A involves analyzing time series data of Covid-19 cases. It includes:
- Creating a function to plot time series for selected countries.
- Standardizing the data using StandardScaler.
- Discussing trends in standardized time series for the US, Canada, and China.

### Part 2: PCA and Eigenvalue Analysis

In Part 2, PCA and eigenvalue analysis are performed on the Covid-19 dataset. This includes:
- Computing the covariance matrix of the dataset.
- Developing functions to obtain sorted eigenvalues and eigenvectors.
- Visualizing principal components with a scree plot.
- Determining the number of principal components needed to cover 98% of dataset variance.
- Plotting the first 16 principal components as time series.
- Comparing trends between the first few principal components and the rest.

### Part 3: Data Reconstruction

Part 3 focuses on data reconstruction using PCA. It includes:
- Creating a function to plot original time series for a specific country and display incremental reconstruction using various principal components.
- Illustrating residual error and RMSE for reconstructions.
- Testing the function with inputs from the US, Canada, and China.

## Project 3B: Fashion MNIST Compression

### Part 1: Getting Started

Part 1 of Project 3B involves preparing the Fashion MNIST dataset for compression. This includes:
- Creating a new dataset by selecting images from only three distinct categories.
- Scaling the data using StandardScaler.

### Part 2: PCA Compression

In Part 2, PCA compression is applied to the Fashion MNIST dataset. This includes:
- Computing eigenvectors and eigenvalues.
- Plotting the first 10 eigenvectors as images.
- Creating a function to plot a random image from the dataset and its reconstruction with the first N principal components.
- Determining the number of components required for human identification.
- Calculating the compression ratio for the dataset.

## Usage

To use the code in this repository, follow the instructions provided in each project's section.

## Installation

Clone the repository to your local machine using:

```bash
git clone https://github.com/your-username/your-repository.git
