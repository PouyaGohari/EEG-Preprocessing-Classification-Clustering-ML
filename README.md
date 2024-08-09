# EEG-Preprocessing-Classification-Clustering-ML
This repository contains code and resources for a Machine Learning project focused on the preprocessing, classification, and clustering of EEG signals as part of a Machine Learning course.

## Table of Contents

- [Introduction](#introduction)
- [Project Description](#project-description)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Data Description](#data-description)
- [Reports](#reports)
- [License](#license)



## Introduction

This repository contains a project developed for a Machine Learning course. The project focuses on the preprocessing, classification, and clustering of EEG signals using various machine learning techniques. The goal is to preprocess EEG data, apply different algorithms, and evaluate their performance in classifying motor imagery tasks, as well as to explore the data through clustering methods.

## Project Description

The project involves preprocessing EEG data, applying machine learning algorithms to classify the signals, and using clustering techniques to identify patterns in the data. Techniques such as CSP (Common Spatial Patterns), ICA (Independent Component Analysis), and various classifiers like SVM, KNN, and Regression are explored alongside clustering algorithms such as K-means and Agglomerative clustering.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3.x installed on your machine.
- Required Python packages installed (`scipy`, `clusteval`, `mne` etc.).
- Basic understanding of Machine Learning, EEG signal processing, and clustering techniques.

## Installation

To clone and run this repository locally, follow these steps:

1. Clone the repository:

   ```sh
   git clone https://github.com/PouyaGohari/EEG-Preprocessing-Classification-Clustering-ML.git
2. Navigate to the project directory:

   ```sh
   cd EEG-Preprocessing-Classification-Clustering-ML


## Usage

1. Open the Jupyter Notebook provided in this repository.
2. Follow the steps in the notebook to:
   - Preprocess the EEG data.
   - Run the machine learning models to classify the EEG signals.
   - Apply clustering algorithms to explore the data and identify patterns.
   - Evaluate the performance of the models and clustering results.

The notebook is self-contained, with detailed instructions and code cells that you can execute sequentially.

## Data Description

The dataset used in this project comes from the BCI Competition IV and contains EEG recordings of motor imagery tasks. The data includes:

- **EEG signals**: Recorded at a sampling rate of 100 Hz.
- **Preprocessed data**: After applying diifferent techniques like Band-pass filter, CAR, Small Laplacian, PCA, ICA and CSP.

More information about the dataset can be found [here](https://www.bbci.de/competition/iv/) and also we provide dataset in our [repo](Data)

## Reports

This project includes two phases, each documented in separate reports:

- **First Report:** Summarizes the previous work, including preprocessing techniques and related research.
  - **Path:** [First Report/ML_Final_Project_phase_1(2)/ml.pdf](First%20Report/ML_Final_Project_phase_1(2)/ml.pdf)

- **Final Report:** Details the preprocessing, classification, and clustering analysis applied to the EEG data.
  - **Path:** [Final Report/FINAL_CA_ML.pdf](Final%20Report/FINAL_CA_ML.pdf)

## License

This project is licensed under the Apache License 2.0 - see the [LICENSE](LICENSE)
